# D-ND Lab

## Summary

D-ND Lab is the exportable Lab layer for self-maintaining agentic R&D workflows.

It turns a domain and an intent into a reviewable operating cycle: live field, tensions, experiments, falsifier, gates, memory, dashboard state and reusable procedures.

D-ND is the logical-operational kernel underneath the Lab. The first public evaluation point is practical: can the Lab preserve intent, expose state, test outputs and avoid promoting what does not hold?

## Position in the architecture

```text
Intent / domain material
        ↓
AI Lab cycle
        ↓
Domain Lab runtime / dashboard
        ↓
Seed / reusable procedure / next cycle
```

Underlying kernel:

```text
D-ND → THIA → AI Lab → Domain Labs / Seeds
```

## Problem

Long AI-assisted work often fails because the system:

- forgets prior decisions;
- repeats weak hypotheses after context loss;
- produces fluent but untested reports;
- hides uncertainty;
- cannot turn verified residue into reusable procedures.

D-ND Lab treats research as a cycle:

```text
field → tension → experiment/tool → falsifier → gate → memory → next move
```

## System

The Lab layer includes:

- domain-independent Lab cycle;
- domain configurations and templates;
- public dashboard/state surface;
- report and cycle traces;
- falsification memory;
- non-promotion and redesign gates;
- seed/promotion lane for stable procedures;
- MetaLab direction for domain + intent → blueprint → Lab template.

## What it shows

- The Lab method can move between domains.
- Claims can be attacked by separate critical poles.
- Failures can become memory instead of disappearing.
- Public dashboards can expose state, uncertainty, verdicts and trajectory.
- Domain-specific work can feed reusable operating patterns.
- A Lab can be evaluated as an operating loop, not only as content.

## What to inspect

- AI Lab: https://d-nd.com/ai-lab
- Lab surface: https://lab.d-nd.com/
- Live dashboard: https://lab.d-nd.com/dashboard/
- D-ND Lab project/repository: https://github.com/GrazianoGuiducci/D-ND_LAB
- Applied Physics/Math Lab: https://github.com/GrazianoGuiducci/dnd-lab-physics

## Status

Active / demonstrated for core Lab surfaces.

Domain transfer and MetaLab installer are in refinement: useful and visible, but not presented as mature automation.
