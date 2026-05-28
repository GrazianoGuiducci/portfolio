# Site Page Spec: Portfolio / Technical Review

Suggested public page:

`https://d-nd.com/portfolio`

## Current Decision

Build this page on `d-nd.com` before the secondary pages `/thia`, `/dnd`,
`/sistema` and `/consapevolezza`.

Reason:

- the homepage now gives a stable first frame for D-ND Model;
- the portfolio page completes the Italian LinkedIn profile with a public,
  inspectable review target;
- after the portfolio page exists, LinkedIn can point to `d-nd.com/portfolio`
  before the English profile pass.

## Goal

Provide a single page that a technical reviewer can open before reading the
portfolio repository.

This is a professional-review page, not a generic services page. It should make
the work legible for companies, research groups, AI-native product teams and
technical collaborators.

## Visual / UX Fit With Current Home

Use the current `d-nd.com` homepage direction:

- dark, quiet, technical surface;
- restrained neon accents already used by the home: green / cyan / amber /
  purple;
- compact cards and thin borders;
- no marketing hero, no generic freelance-service framing;
- content first, proof surfaces immediately visible;
- CTA buttons aligned with current home style.

## Page Sections

1. **Header**
   - Eyebrow: `Portfolio tecnico`
   - Title: `Graziano Guiducci - AI-DND Portfolio`
   - Subtitle: `Dal 2022 sviluppo il livello operativo attorno all'IA agentica: sistemi che preservano il contesto, verificano i propri risultati, ricordano i fallimenti, rendono visibile il proprio stato e integrano le esperienze fatte, migliorandosi ed evolvendo.`
   - Primary CTA: `Mappa delle evidenze`
   - Secondary CTA: `Dashboard Lab`
   - Third CTA: `Repository portfolio`

2. **Review Path**
   - Live system: D-ND Lab dashboard.
   - Core problem: AI continuity, self-verification, rejected-claim memory.
   - Transferable value: methods and tools for making AI agents more
     continuous, verifiable, inspectable and capable of operating across long
     cycles.
   - Reference areas: machine learning / AI awareness; UX-AI / cognitive
     media; logic / semantics / ontology / information theory.
   - Main artifacts: D-ND Lab, d-nd-seed, THIA/Gödel/CEC, Physics Lab, Paper Zero.
   - Trajectory artifact: Anamnesis appears as absorbed precursor inside
     the d-nd-seed story.
   - Evidence: screenshots, reports, public repos, selected cycle outputs.
   - Boundary: mature systems, support architecture, prototypes.

3. **Current Systems**
   - D-ND Lab dashboard
   - Lab runtime repository
   - Seed repository
   - THIA/Gödel/CEC operating surface
   - Main model site

4. **Core Artifacts**
   - Condensed D-ND Kernel
   - Lab System Overview
   - Falsification Memory
   - Case Studies
   - THIA / Gödel / CEC
   - Context Persistence / Anamnesis lineage
   - THIA Skill Taxonomy lineage
   - Semantic OS / KPhi1 trajectory

5. **What to Evaluate**
   - Does the system preserve memory?
   - Does it attack its own claims?
   - Does it expose state clearly?
   - Does it transfer across domains?
   - Does it produce reusable tools?
   - Does the interface reduce latency between human inference, model output
     and system state?

6. **Role Fit**
   - Agentic AI systems.
   - AI-native UX and Human-AI interaction.
   - Evaluation loops, safety and observability.
   - Memory, tool use and context persistence.
   - Research tooling and autonomous Lab workflows.

7. **Evidence Maturity**
   - Live: D-ND Lab dashboard.
   - Active repositories: D-ND Lab and d-nd-seed.
   - Public surface plus internal component: THIA / Gödel / CEC.
   - Applied domain: D-ND Physics Lab.
   - Formal anchor: D-ND Papers / Paper Zero.
   - Lineage: older kernel, interface and cognitive-system projects.

8. **Reference Areas**
   - Machine learning, AI awareness, cognitive kernels and agentic tools.
   - UX-AI design, cognitive media and information-transfer dynamics between
     human, model and system.
   - Logic, semantics, ontology and information theory.

9. **Boundaries**
   - private runtime logs excluded;
   - secrets excluded;
   - raw handovers excluded;
   - selected internal material rewritten for review.

10. **LinkedIn Completion**
   - This page becomes the first Featured link for the Italian LinkedIn profile
     when published.
   - Keep the public URL stable.
   - Add metadata suitable for link preview:
     - title: `Portfolio AI-DND - Graziano Guiducci`
     - description: `Sistemi IA agentici, Lab autonomi, consapevolezza programmabile, CEC, seed installabili e superfici verificabili.`
     - image: reuse a clean D-ND/portfolio preview image or the page hero
       capture.

## Card Model

Each artifact card should include:

- title;
- one-sentence purpose;
- maturity: draft / reviewed / public;
- link to portfolio repo file;
- optional link to live page/dashboard.

## Modal Reader

The site page can open curated Markdown files from the portfolio repository in
modals. This gives a reviewer a fast inspection path before opening GitHub.

Implementation rule:

- modals read curated files from this repository;
- raw private files are never fetched;
- each modal has an `Open on GitHub` link for source inspection;
- long files should have a table of contents or anchor list.

## First Cards

The first viewport should open with current systems:

- D-ND Lab: live autonomous lab system;
- d-nd-seed: active portable AI-coder continuity layer;
- THIA/Gödel/CEC: live operating, crivello and inversion surface;
- Physics Lab: applied transfer;
- Paper Zero: formal kernel.
- Anamnesis: optional absorbed precursor inside the seed/context-continuity card.

## Links To Use

- Portfolio repo: `https://github.com/GrazianoGuiducci/portfolio`
- Evidence map: `https://github.com/GrazianoGuiducci/portfolio/blob/main/docs/reviewer-evidence.md`
- Lab dashboard: `https://lab.d-nd.com/dashboard/`
- D-ND Lab repo: `https://github.com/GrazianoGuiducci/D-ND_LAB`
- d-nd-seed repo: `https://github.com/GrazianoGuiducci/d-nd-seed`
- Gödel / CEC public surface: `https://d-nd.com/godel`
- D-ND Papers: `https://github.com/GrazianoGuiducci/d-nd-papers`

## Recommended First View

The first screen should show:

- title and subtitle;
- 3 CTAs;
- a compact `Valore trasferibile` block;
- a `Maturità delle evidenze` strip or cards:
  - live;
  - repository attivo;
  - superficie pubblica + componente interna;
  - dominio applicato;
  - ancoraggio formale.

## Italian Copy Source

Use `README.md` as the Italian source of truth for:

- opening;
- technical frame;
- transferable value;
- role applications;
- reference areas;
- strongest evidence;
- evidence maturity.

Use `docs/reviewer-evidence.md` as the technical-review source for:

- proof order;
- translated terms;
- role translation;
- maturity signal.
