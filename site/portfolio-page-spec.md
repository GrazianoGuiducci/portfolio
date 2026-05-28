# Site Page Spec: Portfolio / Technical Review

Suggested public page:

`https://d-nd.com/portfolio` or `https://lab.d-nd.com/portfolio.html`

## Goal

Provide a single page that a technical reviewer can open before reading the
portfolio repository.

## Page Sections

1. **Header**
   - Title: `Graziano Guiducci AI-DND Portfolio`
   - Subtitle: `Dal 2022 sviluppo il livello operativo attorno all'IA agentica: memoria, boot, verifica, crivelli decisionali e superfici di stato.`

2. **Review Path**
   - Live system: D-ND Lab dashboard.
   - Core problem: AI continuity, self-verification, rejected-claim memory.
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

6. **Reference Areas**
   - Machine learning, AI awareness, cognitive kernels and agentic tools.
   - UX-AI design, cognitive media and information-transfer dynamics between
     human, model and system.
   - Logic, semantics, ontology and information theory.

7. **Boundaries**
   - private runtime logs excluded;
   - secrets excluded;
   - raw handovers excluded;
   - selected internal material rewritten for review.

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
