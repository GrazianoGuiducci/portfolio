# Site Page Spec: Portfolio / Technical Review

Suggested public page:

`https://d-nd.com/portfolio` or `https://lab.d-nd.com/portfolio.html`

## Goal

Provide a single page that a technical reviewer can open before reading the
portfolio repository.

## Page Sections

1. **Header**
   - Title: `Graziano Guiducci AI-DND Portfolio`
   - Subtitle: `AI systems, cognitive kernels, D-ND logic, autonomous labs, and context-preserving workflows.`

2. **Review Path**
   - Start with D-ND Lab if the reader wants a live system.
   - Start with Papers / Kernel if the reader wants the formal source.
   - Start with Skills / Anamnesis / KPhi1 if the reader wants AI workflow
     architecture.

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
