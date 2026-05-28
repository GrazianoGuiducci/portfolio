# Reviewer Evidence Map

This page is for a technical reviewer who wants to decide quickly whether the
work is real, inspectable, and relevant to advanced AI systems.

## Core Claim

The portfolio demonstrates an operating layer for long-running agentic AI work:
preserving context, testing outputs, exposing state, remembering failures, and
turning repeated failure modes into reusable procedures.

Current LLM limits shape some temporary scaffolds. The deeper evidence is the
durable harness: awareness before action, recoverability, explicit state, human
control, evaluation loops, and portable rules that can outlive the first
implementation.

High-level logic has its own value and a direct operating expression: live
systems, dashboards, guards, evaluation loops, reusable seeds, and domain labs.

## What to Inspect First

| Evidence | Why it matters | Link |
| --- | --- | --- |
| D-ND Lab dashboard | Live state surface for autonomous lab cycles | https://lab.d-nd.com/dashboard/ |
| D-ND Lab repo | Runtime, domains, dashboard, cycle machinery | https://github.com/GrazianoGuiducci/D-ND_LAB |
| d-nd-seed | Active portable AI-coder operating layer: hooks, memory, safety, skills, lab pattern | https://github.com/GrazianoGuiducci/d-nd-seed |
| THIA / Godel | Live operating surface for memory, routing, inversion, and public use | https://d-nd.com/godel |
| Physics Lab | Applied domain that uses the lab engine | https://github.com/GrazianoGuiducci/dnd-lab-physics |
| D-ND Papers | Formal source and Paper Zero | https://github.com/GrazianoGuiducci/d-nd-papers |

## What This Should Prove

- The work is implemented across repositories and live surfaces.
- The same architecture transfers across domains.
- Failures are stored and used to steer later cycles.
- The interface exposes operational state and presents results.
- The research layer and the engineering layer are connected.

## Terms Translated

Some D-ND terms are useful internally and map to technical readings:

| Internal term | Technical reading |
| --- | --- |
| cimitero | rejected-claim memory / negative-results archive |
| seme | seed state / reusable starting configuration |
| campo | active domain state / current working context |
| contro-polo | independent falsifier / adversarial check |
| ciclo | run loop / evaluation cycle |
| autologico | self-referential consistency check |

## Maturity Signal

Read the portfolio in this order:

1. Live and inspectable systems.
2. Support architecture that explains how they work.
3. Formal/research kernel.
4. Earlier systems as trajectory evidence after the current layer is clear.

Repository maturity varies. The strongest current chain is:
seed -> lab runtime -> applied domains -> THIA/Godel operating surface -> live
dashboard.
