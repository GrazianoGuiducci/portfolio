# D-ND Lab System

## Purpose

The Lab is a reusable cycle system for domains where a single LLM answer is not
enough. It keeps state, runs repeated cycles, attacks its own claims, and exposes
the result in a dashboard that a human can inspect.

## Cycle Shape

Each cycle has a simple operating structure:

1. Read the current field.
2. Propose a direction.
3. Attack the direction with a separate critical pole.
4. Produce a verdict.
5. Record what held, what fell, and what should happen next.
6. Update the seed or domain state.

## Key Properties

### Field Memory

The Lab keeps track of hypotheses, baselines, controls, verdicts, rejected
claims, and next actions. The next cycle starts from that field instead of from
an empty prompt.

### Separate Verification

The part that proposes a direction is separated from the part that tries to
break it. This is the basic producer/counter-pole structure.

### Falsification Memory

Rejected or declassified claims are not erased. They become filter memory, so
the system can avoid repeating weak paths.

### Reusable Tools

When a cycle requires code, a schema, a check, or a dashboard view, that artifact
can become part of the domain template.

## Public Surfaces

- Lab dashboard: https://lab.d-nd.com/dashboard/
- Lab home: https://lab.d-nd.com/
- Custom lab intake: https://lab.d-nd.com/start.html
- Installable Lab repository: https://github.com/GrazianoGuiducci/D-ND_LAB

## Active Domain Examples

- Bitcoin Regime Lab: regime hypotheses, method pressure, paper simulation, and
  falsification gates.
- Finance Lab: market regime-shift testing against baselines, costs, and nulls.
- Physics/Math Lab: original research field and discovery pipeline.
- Research Radar: claim monitoring with source/watch/reject discipline.

## Technical Review Notes

The public dashboard is intentionally not just a marketing page. It shows domain
state, cycle traces, rejected material, current verdicts, and operational
status. That makes it useful for evaluating whether the Lab is actually learning
from prior cycles.

