# Universal triadic-stability claim deprecation

Date: 2026-08-16  
Disposition: **DEPRECATED**

## Failed claim

> Dyadic systems oscillate or collapse, while triads stabilize recursion.

## Decisive counterexample

- A two-dimensional diagonal recurrence with eigenvalues `(0.5, 0.5)` is
  stable and non-oscillatory.
- A three-dimensional diagonal recurrence with eigenvalues `(1.1, 1.1, 1.1)`
  is unstable.

After 40 steps from the frozen nonzero initial states, the dyadic norm was
`2.034e-12` and the triadic norm was `78.391`.

The counterexample falsifies the universal arity claim. It does not decide
whether a particular constrained triadic ZFAE implementation can stabilize.

## Replacement

No universal arity rule. Every stability claim must name its dynamics,
constraints, initial-condition class, metric, comparator, and threshold.

ZFAE's current triad remains an instance definition only.

## hmmm

The useful question is not whether three is magically stable; it is which
couplings make this particular three stable, and cheaper than two.
