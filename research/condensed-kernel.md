# Condensed D-ND Kernel

This page is the public-review version of the D-ND condensed kernel. It should
be developed from curated source material, not copied as a raw internal file.

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
- `R + 1 = R` as fixed-point condition, not as a slogan;
- what is a mathematical statement, what is a model interpretation, and what is
  an operational analogy used by the Lab.

## Boundary

Do not publish raw internal notes, boot language, private paths, or operational
state. Curate the kernel into a document that a technical reviewer can inspect.
