# Condensed D-ND Kernel

This page is the public-review version of the D-ND condensed kernel. It should
be developed from curated source material as a clean technical artifact.

## Core Object

The minimal object is:

```text
f(x) = 1 + 1/x
M = [[1, 1], [1, 0]]
tr(M) = 1
det(M) = -1
```

The fixed point is `phi`; the recursive process exposes a rational structure
that generates an irrational fixed point.

## Public Shape

A public page should explain:

- the map;
- the matrix;
- the role of `det(M) = -1`;
- why the first iteration matters;
- `R + 1 = R` as fixed-point condition;
- what is a mathematical statement, what is a model interpretation, and what is
  an operational analogy used by the Lab.

## Boundary

This page should remain a curated kernel document for technical review. Raw
internal notes, boot language, private paths and operational state are outside
its scope.
