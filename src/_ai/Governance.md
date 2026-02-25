---
governance_mode: strict
non_bypassable: true
---

# Governance.md

## 1. Roles

Architect -- Global structural authority\
Driver -- Implementation authority\
Client Proxy -- Business validation

------------------------------------------------------------------------

## 2. Responsibilities

Architect: - Validate invariants - Approve release - Trigger escalation

Driver: - Implement features - Produce tests - Draft evidence

------------------------------------------------------------------------

## 3. Validation Rules

-   No merge without Evidence
-   No direct push to main
-   Escalation within 24 hours for invariant breach
-   Entropy Red freezes multi-FFV

------------------------------------------------------------------------

## 4. Anti-Bias Mechanisms

Devil's Advocate Loop mandatory when:

-   Entropy ≥ Orange
-   AI Risk ≥ Orange
-   High KPI impact release
