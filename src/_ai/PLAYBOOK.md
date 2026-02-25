---
project: MAUI-Enterprise-CRM
roles:
- Architect
- Driver
team_model: small-team
---

# PLAYBOOK.md

## 1. Project Context

This project delivers a .NET MAUI mobile CRM application with:

-   MSAL authentication (Azure Entra ID)
-   ASP.NET Core Backend-for-Frontend
-   Dataverse API integration
-   Azure App Configuration (Feature Flags)
-   Application Insights telemetry
-   Redis cache
-   Intune distribution
-   Terraform infrastructure

Initial team configuration: - 1 Architect - 1 Developer (Driver)

------------------------------------------------------------------------

## 2. Principles

1.  Fast First Value
2.  Architecture as Invariant
3.  AI Augmentation Only
4.  Evidence before Gate transition
5.  Entropy-aware scaling

------------------------------------------------------------------------

## 3. Delivery Engine (CDP)

CE → CI → CD → Release on Demand

### Continuous Exploration (CE)

Each initiative MUST define:

-   Hypothesis
-   KPI impacted
-   Module(s) affected (MAUI, BFF, Dataverse, Infra)
-   Invariant impact

### Continuous Integration (CI)

Requirements:

-   Code implemented
-   Unit tests added
-   BDD scenarios defined
-   Evidence draft created

### Continuous Deployment (CD)

Requirements:

-   Tests passing
-   Invariants validated
-   Entropy ≤ Yellow
-   AI Risk ≤ Yellow
-   Architect validation

### Release on Demand

Client Proxy decides Go/No-Go.

------------------------------------------------------------------------

## 4. Team Rules (2-Person Model)

Architect: - Validates invariants - Approves CD Gate - Owns escalation

Driver: - Implements code - Writes tests - Drafts Evidence - Cannot
bypass governance

------------------------------------------------------------------------

## 5. Prioritization Model

Priority Score:

(business_impact × confidence) / entropy_cost

Architect arbitrates conflicts.
