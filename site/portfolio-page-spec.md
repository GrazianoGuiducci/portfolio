# Site Page Spec: Portfolio / Technical Review

Suggested public page:

`https://d-nd.com/portfolio` or `https://lab.d-nd.com/portfolio.html`

## Goal

Provide a single page that a technical reviewer can open before reading the
portfolio repository.

## Page Sections

1. **Header**
   - Title: `Graziano Guiducci AI-DND Portfolio`
   - Subtitle: `AI systems that preserve context, test their outputs, remember failures, and turn stable procedures into reusable tools.`

2. **Review Path**
   - Live system: D-ND Lab dashboard.
   - Core problem: AI continuity, self-verification, rejected-claim memory.
   - Main artifacts: D-ND Lab, d-nd-seed, Paper Zero, Physics Lab.
   - Trajectory artifact: Anamnesis can appear only as absorbed precursor inside
     the d-nd-seed story.
   - Evidence: screenshots, reports, public repos, selected cycle outputs.
   - Boundary: mature systems, support architecture, prototypes.

3. **Current Systems**
   - D-ND Lab dashboard
   - Lab runtime repository
   - Seed repository
   - Main model site

4. **Core Artifacts**
   - Condensed D-ND Kernel
   - Lab System Overview
   - Falsification Memory
   - Case Studies
   - THIA Skill Taxonomy
   - Context Persistence / Anamnesis
   - Semantic OS / KPhi1 trajectory

5. **What to Evaluate**
   - Does the system preserve memory?
   - Does it attack its own claims?
   - Does it expose state clearly?
   - Does it transfer across domains?
   - Does it produce reusable tools?

6. **Boundaries**
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
modals. This is useful because a reviewer can inspect the work without jumping
immediately into GitHub navigation.

Implementation rule:

- modals read only curated files from this repository;
- raw private files are never fetched;
- each modal has an `Open on GitHub` link for source inspection;
- long files should have a table of contents or anchor list.

## First Cards

The first viewport should not lead with the D-ND theory. It should show:

- D-ND Lab: live autonomous lab system;
- d-nd-seed: active portable AI-coder continuity layer;
- THIA Skills: archived modular agent-capability snapshot;
- Paper Zero: formal kernel;
- Physics Lab: applied transfer.
- Anamnesis: optional absorbed precursor inside the seed/context-continuity card.
