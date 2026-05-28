# Graziano Guiducci AI-DND Portfolio

I build the operating layer around agentic AI: systems that preserve context,
test their own outputs, remember failures, expose state, and turn repeated
failure modes into reusable tools.

This portfolio presents selected work on autonomous labs, cognitive kernels,
semantic interfaces, D-ND logic, context persistence, and long-running agent
workflows. It is written for technical review: what exists, what can be
inspected, what is mature, and what remains experimental.

The work starts from high-level reasoning, but its value is practical: the
logic becomes tools, dashboards, safety guards, evaluation loops, and reusable
operating patterns.

## Start Here

1. [Evidence Map](docs/reviewer-evidence.md) — what to inspect first and why.
2. [D-ND Lab](projects/dnd-lab/README.md) — live autonomous lab system.
3. [d-nd-seed](projects/dnd-seed/README.md) — active portable AI-coder seed,
   hooks, memory, safety, and lab pattern.
4. [THIA Skill Repository](projects/thia-skill-repository/README.md) — archived
   cognitive and operative skills.
5. [D-ND Papers](projects/dnd-papers/README.md) — formal kernel and Paper Zero.
6. [Project Index](projects/index.md) — wider trajectory and maturity levels.
7. [Work Profile](work/one-page-profile.md) — compact profile for roles and
   collaborations.

## The Technical Problem

Long-running AI work breaks when the model loses context, repeats old errors,
produces persuasive text without tests, or hides state from the operator. The
systems in this portfolio address that problem through:

- context continuity across sessions and compaction;
- explicit memory of decisions, failures, and next actions;
- claim/counter-claim loops instead of one-pass generation;
- dashboards that expose live state and uncertainty;
- reusable kernels, skills, and lab templates.

Some scaffolds in this work respond to current model limitations: context
windows, session resets, and explicit boot/reentry procedures. Those techniques
may change as LLMs improve. The durable value is the harness around autonomous
work: awareness before action, state exposure, verification, human control,
failure memory, and promotion of stable operating rules into reusable seeds.

The core claim is simple: repeated failures of AI work can become reusable
operating structures.

## Strongest Evidence

- **D-ND Lab**: a live multi-domain lab runtime with cycles, reports,
  falsification, state dashboard, and reusable domain templates.
- **d-nd-seed**: an active portable seed for AI coders, with hooks, compact
  recovery, safety guards, skills, install profiles, and the Lab pattern.
- **THIA Skill Repository**: an archived but useful snapshot of modular
  cognitive, operative, and bridge faculties for AI agents.
- **D-ND Papers / Paper Zero**: the compact formal source behind the D-ND
  operating logic.
- **D-ND Physics Lab**: applied evidence that the lab engine transfers beyond a
  demo surface.

## Current Public Surfaces

- Main site: https://d-nd.com
- Lab subdomain: https://lab.d-nd.com
- Lab dashboard: https://lab.d-nd.com/dashboard/
- Seed repository: https://github.com/GrazianoGuiducci/d-nd-seed
- Lab repository: https://github.com/GrazianoGuiducci/D-ND_LAB
- Portfolio repository: https://github.com/GrazianoGuiducci/portfolio

## How to Read It

The fastest path is practical first, theory second:

- open the live Lab dashboard;
- read the D-ND Lab and d-nd-seed cards;
- use the evidence map to decide which repository or document to inspect;
- read Paper Zero only after seeing what the systems do.

Older or archived projects are included only when they explain the path toward
the current systems.
