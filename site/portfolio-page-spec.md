# Site Page Spec: Portfolio / Technical Review

Target public page:

`https://d-nd.com/portfolio/`

## Publication boundary

This file is the **source/specification** for the public portfolio projection.

The live `d-nd.com` site has its own publication architecture. Implementation
must be performed through the current **Siteman + Codex** workflow. Updating
this repository does not authorise direct edits, ad-hoc deploys or bypassing
Siteman.

## Current decision

The portfolio remains Graziano Guiducci's technical portfolio. It should not be
turned into a MAIOS product page.

However, the current page is structurally behind the work: it still presents
AI Lab, Domain Labs, Seed, RepoKernel, THIA and other components as a relatively
flat set while MAIOS has become the current operational/public convergence of a
substantial part of the work.

The new reading order should be:

```text
Graziano / current AI-systems work
        ↓
MAIOS — current operational/public convergence
        ↓
what can be used, configured or inspected
        ↓
components, competences and evidence
        ↓
research systems and deeper architecture
        ↓
THIA total-system context / D-ND research source / lineage
```

Public order is not semantic containment: THIA remains the total-system
relation; MAIOS is the current operational/public convergence surface.

## Goal

Make the work legible to companies, professionals, research groups, AI-native
product teams and technical collaborators without forcing them to decode the
project genealogy first.

The page should answer, in this order:

1. Who is Graziano and what kind of AI work is this?
2. What is the current operational result?
3. What can a person or organisation do with it?
4. What capabilities and evidence exist underneath?
5. What is demonstrated, evolving, prototype or lineage?
6. What deeper research direction connects the work?

## Visual / UX constraint

Do **not** redesign the site merely because the hierarchy changes.

Preserve the current `d-nd.com` design system unless a separate design decision
is made through Siteman:

- dark, quiet technical surface;
- restrained green/cyan/amber/purple accents;
- compact cards and thin borders;
- evidence and maturity visible;
- strong information hierarchy;
- no generic agency/freelance visual language.

The main change is semantic and informational: current convergence first,
project catalogue second.

## Proposed page

### 1. Header — person and current work

Eyebrow:

`Portfolio tecnico`

Title:

`Graziano Guiducci — AI Systems Portfolio`

Suggested subtitle:

`Ricerca, progettazione e sviluppo di sistemi IA orientati a continuità,
consapevolezza operativa, evoluzione delle competenze e collaborazione
umano-AI. MAIOS è l'attuale convergenza operativa di una parte sostanziale di
questo lavoro.`

Primary CTA:

- `Apri MAIOS`

Secondary CTAs:

- `Mappa delle evidenze`
- `Repository portfolio`

The header should not enumerate D-ND, THIA, Labs, Seed and every component.

### 2. Current convergence — MAIOS

Featured block/card larger than the component cards.

Title:

`MAIOS — Multi AI Operative System`

Function copy:

`Un ambiente operativo per costruire e far evolvere l'AI attorno a progetti
reali, organizzando Project Kernel, contesto, modelli, strumenti, memoria,
competenze e fonti in una continuità di lavoro verificabile e revisionabile.`

Make visible that the current public experience includes:

- guided Setup AI;
- self-configuring project package / Project Kernel;
- components and ecosystem views;
- contextual chat;
- editorial guidance;
- human consulting route.

Maturity:

`demonstrated / evolving`

Do not make a package version number part of the hero. Release/page copy can
change faster than this portfolio projection.

### 3. Research direction

A concise block explaining what the work tends toward rather than only what has
already been built.

Use three or four concepts:

- **system / operational awareness** — relevant context, state, sources,
  evidence, limits and uncertainty can change action;
- **continuity** — recoverable context, intent and direction through changes of
  session, model, tool or host;
- **autopoietic evolution** — operational experience can become reviewed memory,
  competence and function changes;
- **reviewable autonomy** — proposal, verification, permission and effect
  authority remain distinguishable.

Boundary copy:

`Consapevolezza non significa coscienza soggettiva; autopoiesi non significa
auto-modifica illimitata o autorità indipendente.`

### 4. Capabilities / transferable value

Cards should describe capabilities before repository names.

Suggested set:

- AI systems architecture and integration;
- agentic and multi-AI systems;
- Project Kernel, context and operational memory;
- competence extraction and reusable skills/procedures;
- AI-native UX and human-AI interaction;
- evaluation, falsification, safety and observability;
- research tooling and self-correcting workflows;
- AI setup and application to company/professional contexts.

Each capability may link to one or more evidence surfaces underneath.

### 5. Evidence / components

This is where the current component cards belong.

Suggested priority:

1. RepoKernel / Project Kernel relation.
2. AI Lab.
3. Domain Labs / lab.d-nd.com.
4. d-nd-seed.
5. Agentic UX Skill.
6. D-ND Business Skill.
7. Physics/Math Lab as a stress test.

Each card should show:

- purpose;
- maturity;
- public surface/repository;
- what it proves;
- explicit boundary if relevant.

Do not use the superseded `AI Business Operating Review` name as the current
public Business Skill identity. Historical material may remain accessible as
lineage.

### 6. Semantic architecture

This section should explicitly prevent the public hierarchy from becoming an
architecture error.

Suggested compact diagram:

```text
THIA — total system
│
├─ D-ND — logical/cognitive and research kernel
├─ THIAMAN — manager / architect function
├─ Multi_Agent_OS — distributed presentation / execution surface
└─ operational incarnations
      models · agents · nodes · tools · services

Within the present operational/public field:
MAIOS = current convergence for project-centred AI work
```

If THIAMAN or Multi_Agent_OS would create unnecessary first-contact complexity,
keep them collapsed behind an expandable/deeper architecture view rather than
removing the semantic distinction from the source.

### 7. What to evaluate

Questions:

- Does the project preserve/reconstruct relevant context and direction through
  transitions?
- Are source, evidence, inference, uncertainty and proposal distinguishable?
- Can operational experience become reviewed memory or competence?
- Can weak outputs be challenged or blocked before promotion?
- Are maturity and missing proof explicit?
- Are human review and effect authority distinguishable from generated action?
- Can a new reader enter from a real problem without first learning internal
  terminology?

### 8. Maturity

Use explicit tags:

- `demonstrated`;
- `demonstrated / evolving`;
- `prototype`;
- `planned`;
- `private`;
- `lineage`;
- `not demonstrated` where needed internally to prevent overclaim.

### 9. Evidence path

Recommended visitor path:

1. MAIOS — `https://maios.it`
2. Portfolio page — `https://d-nd.com/portfolio/`
3. RepoKernel — `https://github.com/GrazianoGuiducci/RepoKernel`
4. AI Lab — `https://d-nd.com/ai-lab`
5. Lab surface/dashboard — `https://lab.d-nd.com/`
6. d-nd-seed — `https://github.com/GrazianoGuiducci/d-nd-seed`
7. Agentic UX Skill — `https://github.com/GrazianoGuiducci/d-nd-ux-ai-seed`
8. D-ND Business Skill — `https://github.com/GrazianoGuiducci/dnd-business-skill`
9. THIA/D-ND/deeper research only after the operating evidence is visible.

GitHub portfolio source:

- `https://github.com/GrazianoGuiducci/portfolio`

Reviewer evidence:

- `https://github.com/GrazianoGuiducci/portfolio/blob/main/docs/reviewer-evidence.md`

### 10. Language boundary

Do not open with:

- a catalogue of project names;
- D-ND as a prerequisite;
- consciousness/subjective-experience claims;
- unrestricted self-modification;
- universal automation;
- a promoted Physics claim;
- generic marketing promises.

Open with:

- the person/current work;
- real AI-system problems;
- what exists;
- what can be inspected;
- where the work tends;
- maturity and evidence.

## Metadata candidate

Title:

`AI Systems Portfolio — Graziano Guiducci`

Description:

`Portfolio tecnico di Graziano Guiducci: MAIOS, sistemi agentici e multi-AI,
Project Kernel, consapevolezza operativa, continuità, AI-native UX,
verifica/falsificazione e ricerca sull'evoluzione autopoietica dei sistemi IA.`

Image:

Use a current portfolio/MAIOS-integrated preview generated through the existing
site asset/Siteman workflow. Do not introduce an external one-off asset path.

## Siteman / Codex handoff contract

Before implementation, Codex should read at minimum:

1. `README.md`
2. `docs/portfolio-overview.md`
3. `docs/system-architecture.md`
4. `docs/positioning-and-maturity.md`
5. `docs/public-language-boundary.md`
6. `docs/claim-boundaries.md`
7. `docs/reviewer-evidence.md`
8. `projects/maios/README.md`
9. this file

Then inspect the **current live/site source and Siteman owner-native rules**.
Do not copy this spec mechanically when current site architecture or Siteman
contracts require another implementation form. Preserve the semantic result.
