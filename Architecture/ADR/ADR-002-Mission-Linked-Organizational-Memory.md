# ADR-002: Mission-Linked Organizational Memory

- **Status:** Accepted
- **Date:** 2026-07-11
- **Decision owners:** Founder, Engineering Lane™, Executive Council™

## Context

Decisions, conversations, journal entries, memory records, and graph relationships can become disconnected when they are stored independently. Cougar requires a durable way to reconstruct why work happened and how it changed the organization.

## Decision

Every meaningful organizational record created during a mission must preserve a permanent `missionId` relationship. A mission acts as the primary continuity anchor across executive decisions, conversations, engineering execution, journals, enterprise memory, timeline records, and graph relationships.

## Consequences

### Positive

- Enables Mission Timeline™ and Mission Replay™.
- Improves auditability and historical reconstruction.
- Allows graph inspection by mission.
- Preserves organizational learning across systems.

### Tradeoffs

- All participating modules must accept and validate mission identity.
- Legacy records may require migration or reconciliation.
- Mission creation and retirement rules must remain governed.

## Implementation guidance

- Generate stable mission identifiers once.
- Never silently replace a mission identity.
- Store relationship identifiers in addition to display labels.
- Validate mission references at write time.
- Preserve mission outcomes after temporary Mission Nodes retire.

