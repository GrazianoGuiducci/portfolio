# Evidence Access

This document explains what is public, what is internal, what is repository-based
and what is exposed through public surfaces.

## Principle

The portfolio separates public evidence from internal implementation.

The goal is to make the work reviewable without exposing private runtime state,
sensitive infrastructure, raw logs, credentials, bridge internals, private
handovers or unpublished orchestration.

Public review order is not semantic containment. MAIOS is the current
project-centred operational/public convergence; THIA remains the total-system
relation.

## Public and inspectable

Public evidence includes:

- MAIOS: https://maios.it
- technical portfolio: https://d-nd.com/portfolio/
- main D-ND site: https://d-nd.com
- THIA public surface: https://d-nd.com/thia
- AI Lab: https://d-nd.com/ai-lab
- Lab surface: https://lab.d-nd.com
- Lab dashboard: https://lab.d-nd.com/dashboard/
- seed surface: https://seed.d-nd.com/
- Agentic UX Skill / UX-AI Seed surface: https://seed.d-nd.com/ux-ai/
- kernel_chat repository: https://github.com/GrazianoGuiducci/kernel_chat
- kernel_chat MAIOS page: https://maios.it/conversation-kernel.html
- RepoKernel repository: https://github.com/GrazianoGuiducci/RepoKernel
- d-nd-seed repository: https://github.com/GrazianoGuiducci/d-nd-seed
- Agentic UX Skill repository: https://github.com/GrazianoGuiducci/d-nd-ux-ai-seed
- D-ND Business Skill repository: https://github.com/GrazianoGuiducci/dnd-business-skill
- D-ND Lab repository / runtime documentation: https://github.com/GrazianoGuiducci/D-ND_LAB
- D-ND Physics Lab repository: https://github.com/GrazianoGuiducci/dnd-lab-physics
- D-ND Papers repository: https://github.com/GrazianoGuiducci/d-nd-papers
- portfolio repository: https://github.com/GrazianoGuiducci/portfolio

## Public surface vs public repository

A public surface is a visible interface, page, dashboard or operating surface.

A public repository is inspectable source code or documentation.

Some important parts of the system are best reviewed through public surfaces
rather than direct repository access. MAIOS is currently best understood first
through its public operating surface; GitHub then provides source/evidence for
specific components. THIA is represented publicly through curated surfaces and
architecture because its implementation repository is private.

## MAIOS boundary

MAIOS can be inspected publicly as the current project-centred operational
convergence.

The public surface supports claims about what is actually visible and current:
guided setup, self-configuring project material, Project Kernel/component
explanations, contextual chat, ecosystem/editorial views and a human consulting
route.

Owner-native evidence can support bounded statements about demonstrated Codex
setup/reentry behavior, but private details and broader host compatibility are
not public proof by default.

## kernel_chat boundary

`kernel_chat` is public evidence for a portable conversational kernel, its
ChatGPT host adapter, GitHub persistence adapter, configurator and structural
validator. Version 0.4.0 is a first integrated release.

Repository structure is not proof of real-use assimilation, a second host
adapter or autonomous background operation. ChatGPT and GitHub are the first
implemented edges, not the product's final identity or architectural ceiling.

## THIA boundary

THIA is the **total-system relation / whole ecosystem context**, not merely a
coordination/runtime layer.

The THIA implementation repository is private. That privacy refers to
implementation, not to THIA as a system.

Concrete THIA incarnations can include distributed nodes, runtimes, agents,
services, memory, routing, public/private surfaces and coordination functions.
These are evidence of incarnation, not the complete semantic definition.

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
- MAIOS owner-native implementation details not intentionally public;
- private Business Manager source/state;
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

1. MAIOS;
2. technical portfolio;
3. kernel_chat as the primary conversational-kernel surface;
4. RepoKernel / Project Kernel evidence;
5. AI Lab;
6. Lab surface and dashboard;
7. d-nd-seed and Agentic UX Skill;
8. D-ND Business Skill where business-operating competence is relevant;
9. THIA as total-system context;
10. applied Physics/Math Lab as stress test;
11. D-ND Papers / formal and deeper research anchor.

Private or internal material is discussed only if a serious review requires
deeper detail and an appropriate disclosure boundary exists.
