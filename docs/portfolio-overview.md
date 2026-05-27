# Portfolio Overview

## One-Line Summary

D-ND is a framework and operating system for building AI-assisted labs that run
cycles, test claims against counter-poles, remember failures, and turn stable
patterns into reusable tools.

## What This Shows

- Long-running autonomous cycle design.
- Research workflow with explicit falsification.
- Memory structures that survive context loss and model handoff.
- Public dashboards for reading live lab state.
- Domain transfer: physics/math, finance, Bitcoin regime analysis, research
  radar, and future custom labs.
- Productization path from theory to installable lab templates.

## Why It Matters

Most AI coding and research workflows fail in three places:

- they forget why a decision was made;
- they repeat errors after context compression;
- they produce persuasive text without a falsification loop.

D-ND addresses those failures by treating every output as part of a cycle:
proposal, attack, verdict, memory, next action.

## Current Focus

The recent work is centered on:

- `D-ND_LAB`: installable lab runtime and dashboard.
- `lab.d-nd.com`: public lab interface.
- `d-nd-seed`: portable seed and operating protocols.
- `MM_D-ND`: private research lab and source field for the model.

## Suggested Review Path

For a technical reviewer:

1. Read the [D-ND Lab System](dnd/lab-system.md).
2. Read the [Condensed D-ND Kernel](dnd/condensed-kernel.md).
3. Read the [Falsification Memory](dnd/falsification-memory.md).
4. Open the live dashboard and compare the description to the running system.
5. Review case studies for evidence of transfer across domains.

