# Boundary Tests

This directory contains formal admissibility tests for the MACHWERK framework.

These files are **not demonstrations**, **not examples**, and **not applications**.
They are structural stress tests for the formal core.

Each test examines whether a well-known physical statement remains
**physically admissible** under the conditions defined by:

- projection-based observability
- loss of injectivity (black boundaries)
- relational consistency (CRA axiom)

The purpose of these tests is not to reproduce standard results,
but to determine **which parts of established formulations remain meaningful**
once implicit assumptions are removed.

---

## What these tests are

Boundary tests are formal checks that answer the question:

> Can a given physical statement be formulated without violating
> projection invariance and relational admissibility?

They explicitly operate **at or across Schwarzgrenzen**.

A test may conclude that:
- a statement is admissible
- a statement is admissible only under restriction
- a statement is formally defined but physically inadmissible

No interpretation is added.
No alternative dynamics are proposed.

---

## What these tests are not

Boundary tests are **not**:

- interpretations of quantum mechanics
- alternative physical theories
- simulations or numerical models
- philosophical speculation

They do not introduce new constants, forces, or dimensions.

---

## Included tests

### Bell Admissibility Test

Examines Bell-type correlation statements under non-injective projection.

The test does **not** question quantum statistics.
It checks whether statements referring to distinct underlying states
remain admissible when those states are observationally indistinguishable.

This test directly probes the role of:
- projection collapse
- gauge invariance
- CRA consistency

---

### Mass Origin Test

Examines whether mass-like quantities can be treated as intrinsic
or must be regarded as projection-dependent relational quantities.

Focus:
- stability of mass definitions under projection
- admissibility across m₂ boundaries

---

### Time Correlation Test

Examines time-correlated statements when time is treated
as a derived relational quantity rather than a primitive parameter.

Focus:
- loss of ordering beyond injective domains
- distinction between formal continuation and physical interpretation

---

## Relation to the book

The tests in this directory correspond to formal analyses
presented in the book *MACHWERK — Formal Conditions of Physical Describability*.

This repository does **not** contain the full derivations or narrative context.
It provides the **formal test scaffolding** only.

---

## Reading note

If a boundary test marks a statement as physically inadmissible,
this does **not** mean the statement is false.

It means:
- the statement cannot be uniquely grounded in observable relations
- its interpretation exceeds the admissible projection domain

This distinction is essential to the MACHWERK framework.
