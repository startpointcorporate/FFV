---
team_model: scalable
---

# Role-Mapping.md

## 1. Small Team (2 People)

Architect: - Architecture - Invariants - CD approval

Driver: - Code - Tests - Evidence

------------------------------------------------------------------------

## 2. Scale Team Setup

As team grows:

-   Introduce Module Owners
-   Separate Domain Expert role
-   Add Ops role
-   Split MAUI / BFF ownership

------------------------------------------------------------------------

## 3. Team Capacity Model

Small Team: 1--3 concurrent FFVs max

Scale Team: Concurrency = Modules × 2\
Subject to Entropy threshold

Scaling requires:

-   Entropy ≤ Yellow
-   Health Score ≥ Green
-   Escalation SLA respected
