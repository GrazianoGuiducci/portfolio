# Anamnesis

## Summary

Anamnesis is an archived v0.1 context-persistence pattern for AI coders. It
captures an important problem early: how reasoning survives context-window
compaction, session boundaries, and context variance.

## Problem

Long coding sessions fail when the assistant loses the operational thread:
current goal, files touched, decisions made, alternatives rejected, unresolved
risks, and next exact step. Anamnesis addressed this as a first-class system
problem before the same concern became part of the current continuity and
reentry layer.

## System

The inspected repository presents patterns and templates as an archived design
surface:

- crystallization format for active reasoning;
- pre/post compaction hook templates;
- context map structure;
- recovery instructions after session restart;
- feedback loop to test whether recovery worked.

## What to Inspect

- Repository: https://github.com/GrazianoGuiducci/anamnesis

## Status

Archived public repository. Important as a precursor and conceptual proof of the
context-loss problem. Present it as trajectory evidence until it is updated or
reconnected to the present lab and continuity layer.
