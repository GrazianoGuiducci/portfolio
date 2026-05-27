# Falsification Memory

## Purpose

D-ND does not treat failed claims as waste. Failed claims are part of the
working memory of the system. They explain which paths were tested, why they
fell, and what replaced them.

This document is a public-friendly extract of the private `cimitero.md` file.

## Pattern

Each rejected item should answer:

- What did the claim say?
- What falsified or declassified it?
- What replaced it, if anything?
- What should future cycles avoid repeating?

## Examples

### r-ratio as Prime Signal

The initial idea was that the r-ratio carried direct information about prime
structure. Decomposition showed that the value was explained by the deterministic
sieve structure rather than by independent signal beyond it.

Replacement: use stability and residual structure as the real target, not the
raw ratio.

### Autocorrelation Under M

The initial interpretation treated gap autocorrelation as a structural property
of primes. Shuffle tests showed that most of the effect was mechanical, created
by the shared term in consecutive ratios.

Replacement: isolate the residual signal instead of preserving the full
autocorrelation claim.

### LVL-2 With Phi Target

The initial LVL-2 metric used `phi` as the natural target. Review showed that
the target should be `1` for constant ratios. The metric was declassified until
reformulated.

Replacement: none yet. The tool is suspended.

## Why This Matters

The falsification memory is the practical difference between a research lab and
a persuasive text generator. It forces the system to remember why attractive
claims were rejected.

