# Graziano Guiducci AI-DND Portfolio

I build AI systems that preserve context, test their own outputs, remember
failures, and turn stable reasoning patterns into reusable tools.

This portfolio presents selected work on autonomous labs, cognitive kernels,
semantic interfaces, D-ND logic, context persistence, and long-running agent
workflows. It is written for technical review: what exists, what can be
inspected, what is mature, and what remains experimental.

## Start Here

1. [Evidence Map](docs/reviewer-evidence.md) — what to inspect first and why.
2. [D-ND Lab](projects/dnd-lab/README.md) — live autonomous lab system.
3. [d-nd-seed](projects/dnd-seed/README.md) — active portable AI-coder seed,
   hooks, memory, safety, and lab pattern.
4. [THIA Skill Repository](projects/thia-skill-repository/README.md) — archived
   cognitive and operative skills.
5. [D-ND Papers](projects/dnd-papers/README.md) — formal kernel and Paper Zero.
6. [Project Index](projects/index.md) — wider trajectory and maturity levels.

## The Technical Problem

Long-running AI work breaks when the model loses context, repeats old errors,
produces persuasive text without tests, or hides state from the operator. The
systems in this portfolio address that problem through:

- context continuity across sessions and compaction;
- explicit memory of decisions, failures, and next actions;
- claim/counter-claim loops instead of one-pass generation;
- dashboards that expose live state and uncertainty;
- reusable kernels, skills, and lab templates.

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

## Maturity Boundary

This is not a flat list of projects. The work is grouped by review value:

- **Primary systems**: live or directly inspectable systems that demonstrate the
  core ability.
- **Support architecture**: kernels, skills, papers, and protocols that explain
  how the systems are structured.
- **Prototypes / trajectory**: earlier systems that show the evolution of the
  design, without being presented as current production surfaces.

## Review Boundary

Included:

- public explanations of the model;
- selected lab architecture;
- selected validated findings and negative results;
- public dashboard and site links;
- reusable protocols in cleaned form;
- curated project cards for related repositories.

Excluded:

- secrets, tokens, env files, private accounts;
- raw runtime logs and JSONL traces;
- internal handovers and node-specific boot instructions;
- private operator conversations;
- unreviewed drafts presented as finished work.

## Repository Status

This repository is the review layer. Source repositories remain separate. A
project card may link to a public repo, a live page, a paper, or a curated
excerpt, but it should explain what the reviewer should look at before sending
them into implementation details.
