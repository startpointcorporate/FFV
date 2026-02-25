---
bdd_required: true
delivery_model: CDP
---

# Delivery.md

## 1. Delivery Flow

Draft → ReadyCI → InCI → ReadyCD → Production

Transitions require validation.

------------------------------------------------------------------------

## 2. BDD / ATDD Rules

Each feature MUST include:

Given / When / Then scenario\
KPI statement\
Failure scenario

Example:

Given a user selects an account\
When account is selected\
Then map centers on account location

------------------------------------------------------------------------

## 3. Gates

### Ready-for-CI

Requires: - Hypothesis defined - Domain rule impact declared - Invariant
impact declared

### Ready-for-CD

Requires: - Tests passing - Evidence complete - Entropy within
threshold - AI Risk within threshold

------------------------------------------------------------------------

## 4. Sandbox Usage

Sandbox branch allowed for AI experimentation.\
No production deployment from sandbox.\
No real secrets allowed in prompts.

------------------------------------------------------------------------

## 5. Evidence Framework

Each FFV must include:

-   Hypothesis ID
-   KPI baseline
-   Expected delta
-   Invariant check
-   AI usage disclosure
-   Risk classification
