# MACHWERK — Formal Core

This branch contains the **formal mathematical core** of the MACHWERK framework.

It is intended to be:
- machine-readable
- axiomatic
- non-narrative
- free of interpretation, examples, or prose

The purpose of this core is to define **formal conditions of admissibility**
for physical statements based on relational structures, projections,
and domain stability.

This is **not** a physical theory.
It is a **formal meta-framework**.

---

## Structure

The formal core is organized bottom-up:

1. U-space (pure relational domain)
2. Projection
3. Injectivity and invertibility
4. Validity domains (m₂)
5. Boundary conditions (injectivity loss)
6. Admissibility conditions
7. Consistency axioms (CRA)

Each concept is defined in its own file.
No file assumes definitions that appear later.

---

## Reading order (recommended)

- `u_space.tex`
- `projection_definition.tex`
- `projection_operator.tex`
- `injectivity.tex`
- `m2_domain.tex`
- `black_boundary.tex`
- `projection_admissibility.tex`
- `cra_axiom.tex`

---

## Rule

If a statement cannot be uniquely inverted through the projection,
it is **not physically admissible**, even if mathematically well-defined.

This is a structural rule, not an interpretation.
