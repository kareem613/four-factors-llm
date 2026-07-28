---
theme: dracula
title: Finding the Balance
info: A software development framework for deciding where to allow creativity and where to enforce strictness.
fonts:
  sans: IBM Plex Sans
  serif: Source Serif 4
  mono: IBM Plex Mono
layout: cover
duration: 30min
timer: stopwatch
---

# Finding the Balance

A four-factor framework for working with AI.

<div class="mt-6 text-base opacity-85">
  Kareem Sultan<br>
  <span class="text-cyan-300">linkedin.com/in/kareemsultan</span>
</div>

---

# The Misconception

<div class="grid grid-cols-[1.2fr_1fr] gap-10 mt-10">
  <div>
    <div class="text-2xl font-700 leading-tight">
      Most LLM discussion overweights prompting.
    </div>
    <div class="mt-6 text-lg opacity-85 leading-relaxed">
      Better prompts help, but they are not the main lever for reliable software execution.
    </div>
  </div>
  <div class="rounded-2xl border border-white/15 bg-white/6 p-6">
    <div class="text-sm uppercase tracking-widest opacity-60">Counterpoint</div>
    <div class="mt-4 text-xl leading-snug">
      Performance improves when the work is structured around the task, not when the prompt is merely more clever.
    </div>
  </div>
</div>

---

# The Four Factors

<div class="grid grid-cols-2 gap-5 mt-8">
  <div class="rounded-2xl border border-cyan-400/30 bg-cyan-500/8 p-5">
    <div class="text-xs uppercase tracking-widest text-cyan-300">01</div>
    <div class="mt-2 text-2xl font-700">Current State</div>
    <div class="mt-3 opacity-80">What actually exists right now.</div>
  </div>
  <div class="rounded-2xl border border-pink-400/30 bg-pink-500/8 p-5">
    <div class="text-xs uppercase tracking-widest text-pink-300">02</div>
    <div class="mt-2 text-2xl font-700">Direction</div>
    <div class="mt-3 opacity-80">What should change, and why.</div>
  </div>
  <div class="rounded-2xl border border-amber-400/30 bg-amber-500/8 p-5">
    <div class="text-xs uppercase tracking-widest text-amber-300">03</div>
    <div class="mt-2 text-2xl font-700">Execution Constraints</div>
    <div class="mt-3 opacity-80">How work is constrained and guided.</div>
  </div>
  <div class="rounded-2xl border border-green-400/30 bg-green-500/8 p-5">
    <div class="text-xs uppercase tracking-widest text-green-300">04</div>
    <div class="mt-2 text-2xl font-700">Testable End State</div>
    <div class="mt-3 opacity-80">How success is verified externally.</div>
  </div>
</div>

<div class="mt-8 text-lg opacity-75">
The framework is about how these four factors are defined and respected.
</div>

---

# Two Phases Per Factor

<div class="grid grid-cols-2 gap-8 mt-10">
  <div class="rounded-2xl border border-white/15 bg-white/5 p-6">
    <div class="text-xs uppercase tracking-widest opacity-60">Phase 1</div>
    <div class="mt-2 text-3xl font-700">Definition</div>
    <ul class="mt-5 space-y-3 text-lg opacity-85">
      <li>Deciding</li>
      <li>Clarifying</li>
      <li>Designing</li>
    </ul>
  </div>
  <div class="rounded-2xl border border-white/15 bg-white/5 p-6">
    <div class="text-xs uppercase tracking-widest opacity-60">Phase 2</div>
    <div class="mt-2 text-3xl font-700">Execution</div>
    <ul class="mt-5 space-y-3 text-lg opacity-85">
      <li>Working within the structure</li>
      <li>Making choices under constraints</li>
      <li>Respecting what has already been set</li>
    </ul>
  </div>
</div>

<div class="mt-8 text-lg opacity-75">
The same factor can need different behavior in each phase.
</div>

---

# The Spectrum

<div class="mt-5 rounded-2xl border border-white/15 bg-white/5 p-6">
  <div class="flex items-center gap-3 text-sm uppercase tracking-widest opacity-65">
    <span>High Creativity</span>
    <span class="opacity-40">→</span>
    <span>Medium</span>
    <span class="opacity-40">→</span>
    <span>Low</span>
    <span class="opacity-40">→</span>
    <span>No Creativity</span>
  </div>
  <div class="mt-5 h-4 rounded-full bg-gradient-to-r from-pink-500 via-amber-400 to-cyan-300"></div>
</div>

<div class="grid grid-cols-2 gap-8 mt-8 text-lg">
  <div>
    <div class="font-700">High creativity</div>
    <div class="mt-2 opacity-80">Broad acceptable variance. Many valid outputs may exist.</div>
    <div class="mt-5 font-700">Medium creativity</div>
    <div class="mt-2 opacity-80">Bounded variance. Judgment is allowed inside visible limits.</div>
  </div>
  <div>
    <div class="font-700">Low creativity</div>
    <div class="mt-2 opacity-80">Narrow variance. Most work should conform to existing constraints.</div>
    <div class="mt-5 font-700">No creativity</div>
    <div class="mt-2 opacity-80">Zero acceptable variance. Strict adherence or binary verification.</div>
  </div>
</div>

<div class="mt-8 text-xl font-600 text-amber-300">
Be strict where variance is costly. Leave room where variance is useful.
</div>

---
hide: true
---

# Comparing Methodologies (Toggle View)

<div class="mt-2 text-sm uppercase tracking-widest opacity-60">Definition vs Execution Variance by Factor</div>

<div class="mt-1 flex items-center justify-between gap-3 text-[10px] leading-none opacity-90">
  <div class="flex flex-wrap items-center gap-1.5">
    <span class="rounded-full border border-red-300/35 bg-red-500/10 px-2 py-0.5"><span class="font-700 text-red-300">↑</span> High</span>
    <span class="rounded-full border border-amber-300/35 bg-amber-500/10 px-2 py-0.5"><span class="font-700 text-amber-300">■</span> Medium</span>
    <span class="rounded-full border border-lime-300/35 bg-lime-500/10 px-2 py-0.5"><span class="font-700 text-lime-300">↓</span> Low</span>
    <span class="rounded-full border border-slate-300/35 bg-slate-500/10 px-2 py-0.5"><span class="font-700 text-slate-200">—</span> None</span>
  </div>

  <div class="flex items-center gap-2 text-[0.56rem] leading-none">
    <button
      class="rounded-full border px-2 py-0.5 uppercase tracking-[0.08em]"
      :class="methodologyViewMode === 'def' ? 'border-cyan-300/50 bg-cyan-500/15 text-cyan-200' : 'border-white/20 bg-white/5 text-white/70'"
      @click="methodologyViewMode = 'def'"
    >
      Show Def
    </button>
    <button
      class="rounded-full border px-2 py-0.5 uppercase tracking-[0.08em]"
      :class="methodologyViewMode === 'exec' ? 'border-amber-300/50 bg-amber-500/15 text-amber-200' : 'border-white/20 bg-white/5 text-white/70'"
      @click="methodologyViewMode = 'exec'"
    >
      Show Exec
    </button>
    <div class="ml-1 uppercase tracking-[0.08em] opacity-70">
      Showing: <span class="font-700" :class="methodologyViewMode === 'def' ? 'text-cyan-200' : 'text-amber-200'">{{ methodologyViewMode.toUpperCase() }}</span>
    </div>
  </div>
</div>

<script setup lang="ts">
import { ref } from 'vue'

const methodologyViewMode = ref<'def' | 'exec'>('def')

type MethodologyLevel = 0 | 1 | 2 | 3
type MethodologyPhaseLevels = { def: MethodologyLevel; exec: MethodologyLevel }

type MethodologyToggleRow = {
  method: string
  currentState: MethodologyPhaseLevels
  direction: MethodologyPhaseLevels
  constraints: MethodologyPhaseLevels
  endState: MethodologyPhaseLevels
  outcome: string
}

const methodologyToggleRows: MethodologyToggleRow[] = [
  {
    method: 'Traditional Development',
    currentState: { def: 2, exec: 1 },
    direction: { def: 2, exec: 1 },
    constraints: { def: 2, exec: 1 },
    endState: { def: 1, exec: 0 },
    outcome: 'Reliable output with stronger up-front planning and slower definition.',
  },
  {
    method: 'Vibe Coding',
    currentState: { def: 2, exec: 2 },
    direction: { def: 3, exec: 3 },
    constraints: { def: 1, exec: 3 },
    endState: { def: 1, exec: 1 },
    outcome: 'Fast-feeling execution with high variance and uneven validation quality.',
  },
  {
    method: 'Spec-Driven Development',
    currentState: { def: 1, exec: 1 },
    direction: { def: 3, exec: 1 },
    constraints: { def: 1, exec: 2 },
    endState: { def: 1, exec: 0 },
    outcome: 'Better intent capture, but execution quality can vary without strong constraints.',
  },
  {
    method: 'Constraint-Guided Development',
    currentState: { def: 1, exec: 1 },
    direction: { def: 3, exec: 1 },
    constraints: { def: 3, exec: 0 },
    endState: { def: 3, exec: 0 },
    outcome: 'High repeatability by moving creativity into system design, not runtime variance.',
  },
  {
    method: 'Fully Agentic',
    currentState: { def: 1, exec: 1 },
    direction: { def: 3, exec: 1 },
    constraints: { def: 2, exec: 2 },
    endState: { def: 3, exec: 0 },
    outcome: 'Strong automation when critical constraints and verification are explicit.',
  },
]

const methodologyLevelSymbol: Record<MethodologyLevel, string> = {
  3: '↑',
  2: '■',
  1: '↓',
  0: '—',
}

const methodologyLevelClass: Record<MethodologyLevel, string> = {
  3: 'text-red-300',
  2: 'text-amber-300',
  1: 'text-lime-300',
  0: 'text-slate-200',
}

const methodologySymbolFor = (level: MethodologyLevel) => methodologyLevelSymbol[level]
const methodologyClassFor = (level: MethodologyLevel) => methodologyLevelClass[level]
</script>

<div class="mt-1 text-[0.56rem] leading-none overflow-x-auto">
  <table class="methodology-table w-full border-separate border-spacing-y-0 leading-none">
    <thead>
      <tr class="uppercase tracking-[0.06em] opacity-75">
        <th class="method-col text-left pr-2">Method</th>
        <th class="text-center">Current State</th>
        <th class="text-center">Direction</th>
        <th class="text-center">Constraints</th>
        <th class="text-center">Testable End State</th>
        <th class="outcome-col text-left pl-2">Results</th>
      </tr>
    </thead>
    <tbody>
      <tr v-for="row in methodologyToggleRows" :key="row.method">
        <td class="method-col pr-2 align-middle">{{ row.method }}</td>
        <td class="text-center font-700" :class="methodologyClassFor(row.currentState[methodologyViewMode])">{{ methodologySymbolFor(row.currentState[methodologyViewMode]) }}</td>
        <td class="text-center font-700" :class="methodologyClassFor(row.direction[methodologyViewMode])">{{ methodologySymbolFor(row.direction[methodologyViewMode]) }}</td>
        <td class="text-center font-700" :class="methodologyClassFor(row.constraints[methodologyViewMode])">{{ methodologySymbolFor(row.constraints[methodologyViewMode]) }}</td>
        <td class="text-center font-700" :class="methodologyClassFor(row.endState[methodologyViewMode])">{{ methodologySymbolFor(row.endState[methodologyViewMode]) }}</td>
        <td class="outcome-col pl-2 align-middle">{{ row.outcome }}</td>
      </tr>
    </tbody>
  </table>
</div>

<style>
.methodology-table {
  table-layout: fixed;
}

.methodology-table th,
.methodology-table td {
  padding-top: 0.08rem;
  padding-bottom: 0.08rem;
  line-height: 1;
}

.methodology-table .method-col,
.methodology-table .outcome-col {
  font-size: 0.72rem;
  line-height: 1.2;
}

.methodology-table .method-col {
  width: 16%;
}

.methodology-table .outcome-col {
  width: 30%;
  white-space: normal;
}

.methodology-table th:nth-child(n + 2):nth-child(-n + 5),
.methodology-table td:nth-child(n + 2):nth-child(-n + 5) {
  white-space: normal;
  text-align: center;
}

.methodology-table tbody tr + tr td {
  padding-top: 0.22rem;
}
</style>

<div class="mt-2 opacity-80">
Methods differ less by prompting style and more by where they place variance in definition and execution across the four factors.
</div>

---

# Comparing Methodologies

<div class="mt-4 text-sm uppercase tracking-widest opacity-60">Where do methods concentrate creativity and strictness?</div>

| Method | Shape | Typical Tradeoff |
| --- | --- | --- |
| Traditional Development | More structure up front | Reliable, but slower to define |
| Vibe Coding | Minimal structure, high improvisation | Fast feeling, high variance |
| Spec-Driven Development | Strong direction, weaker rails | Better intent, uneven execution |
| Rail Guided Development | High structure across factors | Strong repeatability |
| Fully Agentic | Automation with selective constraints | Works best when critical items are explicit |

<div class="mt-6 opacity-78">
Methodologies differ mostly in where they allow variance and where they force strictness.
</div>

---
layout: two-cols-header
---

# Factor 1: Current State

::left::

**Definition Phase**

Low to Medium Creativity

Building a usable view of reality may require synthesis, interpretation, and cleanup.

**Execution Phase**

Low Creativity

Once established, it should be treated as ground truth. Summarize it if needed, but do not reinvent it.

::right::

**Examples**

- Source code
- Docs
- Architecture diagrams
- Test suites

---
layout: two-cols-header
---

# Factor 2: Direction

::left::

**Definition Phase**

High Creativity

Direction requires goal-setting, reframing, prioritization, and solution exploration.

**Execution Phase**

Low Creativity

Implementation should preserve intent while still allowing flexibility in realization.

::right::

**Examples**

- Product goals
- Feature intent
- Acceptance criteria
- Priority tradeoffs

---
layout: two-cols-header
---

# Factor 3: Execution Constraints

::left::

<div class="text-xs uppercase tracking-widest text-amber-300 opacity-85">Definition Phase</div>
<div class="mt-1 text-2xl font-700">Medium Creativity</div>
<div class="mt-2 text-base leading-relaxed opacity-82">
  Designing constraints requires judgment about process, risk, and the right amount of strictness.
</div>

<div class="mt-5 text-xs uppercase tracking-widest text-amber-300 opacity-85">Execution Phase</div>
<div class="mt-1 text-2xl font-700">Low to None</div>
<div class="mt-2 text-base leading-relaxed opacity-82">
  Follow constraints consistently, with flexibility only where the constraints intentionally leave room.
</div>

::right::

**Examples**

- Execution plan
- Class diagrams
- API specs

---
layout: two-cols-header
---

# Factor 4: Testable End State

::left::

**Definition Phase**

Low Creativity

Defining validation takes care and precision, but the goal is exactness, not openness.

**Execution Phase**

No Creativity

This is where variance is most expensive. Success should be binary and externally verifiable.

::right::

**Examples**

- Unit tests
- Integration tests
- Performance budgets
- Acceptance checks

---

# Software Implications

<div class="grid grid-cols-2 gap-8 mt-8">
  <div class="rounded-2xl border border-green-400/25 bg-green-500/8 p-6">
    <div class="text-sm uppercase tracking-widest text-green-300">Highest Strictness</div>
    <ul class="mt-4 space-y-3 text-lg">
      <li>Tests and validation</li>
      <li>Safety constraints</li>
      <li>Required interfaces</li>
      <li>Compliance boundaries</li>
    </ul>
  </div>
  <div class="rounded-2xl border border-pink-400/25 bg-pink-500/8 p-6">
    <div class="text-sm uppercase tracking-widest text-pink-300">Useful Flexibility</div>
    <ul class="mt-4 space-y-3 text-lg">
      <li>Implementation details</li>
      <li>Refactors</li>
      <li>Internal decomposition</li>
      <li>Solution exploration</li>
    </ul>
  </div>
</div>

<div class="mt-8 text-xl opacity-82">
Software teams get the most leverage by being selective about where variance is allowed.
</div>

---

# Finding a Balance

<div class="mt-4 grid grid-cols-2 gap-4 items-stretch">
  <div class="rounded-2xl border border-pink-400/25 bg-pink-500/8 p-4">
    <div class="text-xs uppercase tracking-widest text-pink-300 opacity-90">Too Few Constraints</div>
    <div class="mt-2 text-xl font-700 leading-tight">Not professional software development</div>
    <div class="mt-3 text-sm leading-relaxed opacity-80">
      The work drifts, quality varies, and execution becomes hard to trust.
    </div>
  </div>

  <div class="rounded-2xl border border-cyan-400/25 bg-cyan-500/8 p-4">
    <div class="text-xs uppercase tracking-widest text-cyan-300 opacity-90">Too Many Constraints</div>
    <div class="mt-2 text-xl font-700 leading-tight">You might as well write it yourself</div>
    <div class="mt-3 text-sm leading-relaxed opacity-80">
      The specification overhead becomes so heavy that the leverage disappears.
    </div>
  </div>
</div>

<div class="mt-4 rounded-2xl border border-amber-400/30 bg-amber-500/12 p-4">
  <div class="text-xs uppercase tracking-[0.2em] text-amber-300 opacity-95">A Balance Range</div>
  <div class="mt-2 text-xl font-700 leading-tight">A wide range can still be good balance</div>
  <div class="mt-3 text-sm leading-relaxed opacity-85">
    Not maximum control. Not maximum speed. Enough structure to protect what matters without specifying so much that you lose the speed benefit.
  </div>
</div>

<div class="mt-3 rounded-xl border border-white/10 bg-white/4 px-3 py-2">
  <div class="grid grid-cols-[0.9fr_2.8fr_0.9fr] gap-2 h-5 text-[9px] font-700 uppercase tracking-[0.14em]">
    <div class="rounded-full bg-pink-500/75 text-white/90 flex items-center justify-center">Too Few</div>
    <div class="rounded-full bg-amber-400/80 text-slate-950 flex items-center justify-center">Good Balance</div>
    <div class="rounded-full bg-cyan-500/75 text-white/90 flex items-center justify-center">Too Many</div>
  </div>
</div>

---

# Balance Depends on Context

<div class="mt-4 rounded-xl border border-white/10 bg-white/4 px-3 py-2">
  <div class="grid grid-cols-[0.9fr_2.8fr_0.9fr] gap-2 h-5 text-[9px] font-700 uppercase tracking-[0.14em]">
    <div class="rounded-full bg-pink-500/75 text-white/90 flex items-center justify-center">Too Few</div>
    <div class="rounded-full bg-amber-400/80 text-slate-950 flex items-center justify-center">Good Balance</div>
    <div class="rounded-full bg-cyan-500/75 text-white/90 flex items-center justify-center">Too Many</div>
  </div>
</div>

<div class="mt-5 grid grid-cols-3 gap-4 items-stretch">
  <div class="rounded-2xl border border-amber-400/20 bg-amber-500/8 p-4">
    <div class="text-xs uppercase tracking-widest text-amber-300 opacity-90">Not Perfectly Optimized</div>
    <div class="mt-2 text-lg font-700 leading-tight">Good balance is a range, not a point.</div>
    <div class="mt-3 text-sm leading-relaxed opacity-80">
      You do not need to optimize constraints perfectly. Many different choices can still be effective.
    </div>
  </div>

  <div class="rounded-2xl border border-cyan-400/20 bg-cyan-500/8 p-4">
    <div class="text-xs uppercase tracking-widest text-cyan-300 opacity-90">Varies By Project</div>
    <div class="mt-2 text-lg font-700 leading-tight">Different work justifies different structure.</div>
    <div class="mt-3 text-sm leading-relaxed opacity-80">
      Higher-risk or more repeatable projects can justify more constraints. Exploratory projects often need fewer.
    </div>
  </div>

  <div class="rounded-2xl border border-pink-400/20 bg-pink-500/8 p-4">
    <div class="text-xs uppercase tracking-widest text-pink-300 opacity-90">Varies By Phase</div>
    <div class="mt-2 text-lg font-700 leading-tight">The same project may move along the range.</div>
    <div class="mt-3 text-sm leading-relaxed opacity-80">
      Early exploration may allow more variance. Later implementation and validation often need tighter control.
    </div>
  </div>
</div>

<div class="mt-5 text-lg opacity-82 leading-relaxed max-w-5xl">
  The right balance is situational. The job is not to find one perfect setting, but to choose a defensible range for the work in front of you.
</div>

---

# Time Allocation With LLMs

| Phase | Refinement | Specs | Implementing | Code Review |
| --- | --- | --- | --- | --- |
| **Pre-AI** | 5% | 5% | 80% | 10% |
| **Naive AI** | 5% | 15% | 5% | 75% |
| **Mature AI** | ~0%<sup>1</sup> | 90% | 5% | 5%<sup>2</sup> |

<div class="mt-6 rounded-2xl border border-amber-400/25 bg-amber-500/8 p-5">
  <ul class="space-y-3 text-lg leading-relaxed opacity-90">
    <li>Naive AI use often <span class="text-pink-300 font-700">moves effort</span> from implementation into code review and correction loops.</li>
    <li>Effort can be shifted upstream into <span class="text-cyan-300 font-700">problem framing and specification</span>, so execution is faster and review is lighter.</li>
    <li><sup>1</sup> Team refinement time is mostly replaced with quick iterations.</li>
    <li><sup>2</sup> End game: code reviews are replaced by spec reviews.</li>
  </ul>
</div>

---

# Practical Operating Principle

<div class="mt-8 grid grid-cols-[1.2fr_1fr] gap-8">
  <div>
    <ol class="space-y-4 text-xl leading-relaxed">
      <li>Define the <span class="text-cyan-300 font-700">current state</span> clearly enough to trust it.</li>
      <li>Define <span class="text-pink-300 font-700">direction</span> creatively enough to choose the right path.</li>
      <li>Define <span class="text-amber-300 font-700">constraints</span> tightly enough to protect what matters.</li>
      <li>Define a <span class="text-green-300 font-700">testable end state</span> precisely enough to verify success objectively.</li>
    </ol>
  </div>
  <div class="rounded-2xl border border-white/15 bg-white/6 p-6">
    <div class="text-sm uppercase tracking-widest opacity-60">Closing Line</div>
    <div class="mt-4 text-2xl leading-snug font-700">
      LLMs work better when boundaries are explicit, not when prompts are merely more clever.
    </div>
  </div>
</div>

---

# Key Takeaways

<div class="mt-8 space-y-6 max-w-5xl">
  <div class="text-3xl leading-tight font-700 text-cyan-300">
    Methodology matters more than prompt cleverness.
  </div>
  <div class="text-3xl leading-tight font-700 text-amber-300">
    Good balance is a range, not a perfect point.
  </div>
  <div class="text-3xl leading-tight font-700 text-pink-300">
    Be strict where variance is costly, and flexible where it is useful.
  </div>
</div>

<div class="mt-10 text-base opacity-80">
  Kareem Sultan<br>
  <span class="text-cyan-300">linkedin.com/in/kareemsultan</span>
</div>
