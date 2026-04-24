# Creating Another Deck with This Stack

This repository is set up for Slidev presentations with Vue components and ECharts-based data visuals.

## 1. Tech Stack Used

- Slidev (`@slidev/cli`)
- Theme: `@slidev/theme-bricks`
- Vue components inside slides
- Charts: `echarts` + `vue-echarts`
- Optional diagram generation scripts in `scripts/`

## 2. Prerequisites

- Node.js 18+
- npm 9+
- A modern browser for local preview

## 3. Initial Setup

Install dependencies once at the project root:

```bash
npm install
```

Run the current default deck:

```bash
npm run dev
```

## 4. Create a New Deck File

Create a new Slidev entry file at the root, for example:

- `slides-ai-ops.md`
- `slides-customer-pov.md`

Start from this minimal template:

```md
---
theme: bricks
title: Your Deck Title
info: One-line subtitle or value statement.
fonts:
  sans: IBM Plex Sans
  serif: Source Serif 4
  mono: IBM Plex Mono
layout: cover
duration: 30min
timer: stopwatch
---

# Your Title Slide

Subtitle or presenter details

---

# Agenda

- Topic 1
- Topic 2
- Topic 3
```

## 5. Run and Build a Specific Deck

Use `npx` commands when working with any deck file besides `slides.md`:

```bash
npx slidev slides-ai-ops.md
npx slidev build slides-ai-ops.md
npx slidev export slides-ai-ops.md
```

Use existing npm scripts for the default `slides.md` entry:

```bash
npm run dev
npm run build
npm run export
```

## 6. Reuse Components and Patterns

Keep reusable UI and charts in `components/`, then import or reference them in your new deck.

Recommended pattern:

1. Build chart or visual component in `components/`.
2. Register only required ECharts modules in that component.
3. Keep chart options and data in the component, not inline in slide markdown.
4. Embed the component in your slide.

Example:

```md
---
layout: two-cols-header
---

# Demand Trend

::left::

- Talking point A
- Talking point B

::right::

<ProjectDemandChart />
```

## 7. Charting Conventions (Project Standard)

- Prefer ECharts (`vue-echarts`) for data charts.
- Prefer SVG rendering for crisp exported output.
- Avoid Mermaid for dense/multi-series charts that need precise legends and axis control.
- Keep visual tuning (size, spacing, labels) inside component CSS/options.

## 8. Asset and Script Workflow

- Put deck images in `images/`.
- Use `scripts/` for helper generators when needed (for example architecture diagrams).
- Commit generated assets that are referenced by slides.

## 9. Recommended Content Workflow

1. Draft narrative in `outline.md` or a topic-specific outline file.
2. Build slides in a new `slides-*.md` file.
3. Add/adjust reusable components in `components/`.
4. Validate presenter flow in local dev mode.
5. Build and export final deliverables.

## 10. Quality Checklist Before Sharing

- Deck loads without runtime errors.
- All custom components render correctly.
- Charts are readable on projector-sized screens.
- Speaker notes are in place where needed.
- Build (`npx slidev build <deck>.md`) succeeds.
- Export (`npx slidev export <deck>.md`) succeeds if PDF is needed.

## 11. Optional: Add Convenience npm Scripts

If you frequently switch decks, add helper scripts in `package.json` such as:

```json
{
  "scripts": {
    "dev:ai-ops": "slidev slides-ai-ops.md",
    "build:ai-ops": "slidev build slides-ai-ops.md",
    "export:ai-ops": "slidev export slides-ai-ops.md"
  }
}
```

This is optional; `npx slidev <deck-file>` is enough for ad hoc decks.
