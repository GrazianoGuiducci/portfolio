# Reviewer Evidence Map

This page is for a technical reviewer who wants to decide quickly whether the
work is real, inspectable, and relevant to advanced AI systems.

## Core Claim

The portfolio demonstrates systems for long-running AI work: preserving context,
testing outputs, exposing state, remembering failures, and turning stable
procedures into reusable tools.

## What to Inspect First

| Evidence | Why it matters | Link |
| --- | --- | --- |
| D-ND Lab dashboard | Live state surface for autonomous lab cycles | https://lab.d-nd.com/dashboard/ |
| D-ND Lab repo | Runtime, domains, dashboard, cycle machinery | https://github.com/GrazianoGuiducci/D-ND_LAB |
| Anamnesis | Direct answer to context loss in AI coding workflows | https://github.com/GrazianoGuiducci/anamnesis |
| THIA Skill Repository | Modular skill architecture for agent behavior | https://github.com/GrazianoGuiducci/skill |
| D-ND Papers | Formal source and Paper Zero | https://github.com/GrazianoGuiducci/d-nd-papers |
| Physics Lab | Applied domain that uses the lab engine | https://github.com/GrazianoGuiducci/dnd-lab-physics |

## What This Should Prove

- The work is implemented across repositories and live surfaces.
- The same architecture transfers across domains.
- Failures are not hidden; they are remembered and used to steer later cycles.
- The interface is used to expose operational state, not just present results.
- The research layer and the engineering layer are connected.

## Terms Translated

Some D-ND terms are useful internally but should be read technically:

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
4. Prototypes and earlier systems as trajectory evidence.

Do not treat every repository as equally mature. The value is in the chain:
kernel -> skills/protocols -> lab runtime -> applied domains -> live dashboard.
