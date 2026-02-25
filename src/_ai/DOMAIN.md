---
domain: CRM-Mobile
---

# DOMAIN.md

## 1. Domain Glossary

Account -- Business client entity\
Opportunity -- Revenue potential record\
Quote -- Commercial offer\
Appointment -- Calendar event\
Meeting Minutes -- Summary captured via speech-to-text\
Visit Planner -- AI-generated weekly visit suggestions\
BFF -- Backend for Frontend\
Dataverse -- External CRM data platform

------------------------------------------------------------------------

## 2. Business Rules

BR-001: Appointment must have at least one attendee.\
BR-002: All API calls require MSAL token.\
BR-003: Account Map and Account List must remain synchronized.\
BR-004: Feature flags must not bypass authorization.

------------------------------------------------------------------------

## 3. Functional Invariants

FI-001: Authentication required for all endpoints.\
FI-002: BFF is the only integration layer to Dataverse.\
FI-003: Redis cache must not store PII unencrypted.\
FI-004: Telemetry must be enabled for all releases.
