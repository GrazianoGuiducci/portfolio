# Evidence Access

This document explains what is public, what is internal, what is repository-based and what is exposed through public surfaces.

## Principle

The portfolio separates public evidence from internal implementation.

The goal is to make the work reviewable without exposing private runtime state, sensitive infrastructure, raw logs, credentials, bridge internals, private handovers or unpublished orchestration.

## Public and inspectable

Public evidence includes:

- main D-ND site: https://d-nd.com
- THIA public surface: https://d-nd.com/thia
- AI Lab: https://d-nd.com/ai-lab
- Lab surface: https://lab.d-nd.com
- Lab dashboard: https://lab.d-nd.com/dashboard/
- seed surface: https://seed.d-nd.com/
- UX-AI Seed surface: https://seed.d-nd.com/ux-ai/
- d-nd-seed repository: https://github.com/GrazianoGuiducci/d-nd-seed
- UX-AI Seed repository: https://github.com/GrazianoGuiducci/d-nd-ux-ai-seed
- D-ND Lab repository / runtime documentation: https://github.com/GrazianoGuiducci/D-ND_LAB
- D-ND Physics Lab repository: https://github.com/GrazianoGuiducci/dnd-lab-physics
- D-ND Papers repository: https://github.com/GrazianoGuiducci/d-nd-papers
- portfolio repository: https://github.com/GrazianoGuiducci/portfolio

## Public surface vs public repository

A public surface is a visible interface, page, dashboard or operating surface.

A public repository is inspectable source code or documentation.

Some important parts of the system are best reviewed through public surfaces rather than direct repository access. This is especially true for THIA and any runtime-connected surface.

## THIA boundary

THIA is the coordination/runtime layer of the D-ND ecosystem.

The THIA implementation repository is private. That privacy refers to implementation, not to THIA as a system.

THIA should be reviewed through:

- the main site;
- the THIA page;
- screenshots;
- architecture summaries;
- public behavior descriptions;
- selected diagrams;
- review-safe documentation.

## Private or partially private

Private or partially private material may include:

- THIA implementation repository;
- runtime state;
- raw logs;
- JSONL traces;
- private handovers;
- unpublished orchestration;
- internal memory;
- credentials and environment files;
- active infrastructure;
- operator conversations;
- experimental code not ready for review.

## How private systems are represented

Private systems can still be made reviewable through:

- public operating surfaces;
- architecture summaries;
- screenshots;
- maturity notes;
- case studies;
- behavior descriptions;
- curated excerpts;
- review material available on request.

## Review path

A technical reviewer should start with public evidence:

1. main D-ND site;
2. THIA public surface;
3. AI Lab;
4. Lab surface and dashboard;
5. d-nd-seed;
6. UX-AI Seed;
7. D-ND Lab runtime / project card;
8. applied Physics/Math Lab as stress test;
9. D-ND Papers / formal anchor.

Private or internal material is discussed only if a serious review requires deeper detail.
