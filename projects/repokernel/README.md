# RepoKernel

Status: public source / product architecture candidate / adoption guide active

RepoKernel is a project-kernel package for AI-assisted repositories and
projects. It gives a coder or agentic system a way to preserve context,
sources, gates, receipts, update awareness and reentry across sessions.

## What It Does

RepoKernel helps a project carry:

```text
current state;
source atlas;
semantic project kernel;
review gates;
receipts;
memory deltas;
update/adoption rules;
first safe action for the next room.
```

It does not automatically rewrite a project. It stages, explains, proposes and
waits for owner gates before adoption.

## Evidence

```text
source repo:
  https://github.com/GrazianoGuiducci/RepoKernel

update path:
  CHANGELOG.md
  CAPABILITIES.md
  docs/update-and-adoption.md

public review assets:
  docs/public/repokernel-portfolio-card.md
  docs/public/repokernel-project-page.md
```

## Useful When

- a coder enters a project and needs to understand what matters before acting;
- a project has many files, chats, decisions and handoffs;
- a team wants source-aware AI assistance without hidden authority;
- an external reviewer needs to see sources, gates and next action clearly;
- a new skill or capability must be noticed without automatic mutation.

## Boundary

No automatic update, hook activation, repository mutation, public claim or
runtime authority is implied. Hooks may remind a check in systems that support
them; they do not grant authority.

## Relationship To AI Business Operating Review

RepoKernel works on project/repository continuity.

AI Business Operating Review works on the business layer around the project:
public surface, offer route, evidence, follow-up and next business action.

Together:

```text
project continuity -> business continuity -> reviewable public proof
```

## Next Proof

Use RepoKernel on one sanitized project or folder and show the staged output:
source map, current state, update awareness, proposed delta and first safe
next action.

