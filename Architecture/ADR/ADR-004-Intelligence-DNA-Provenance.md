# ADR-004: Intelligence DNA™ Provenance Standard

- **Status:** Accepted
- **Date:** 2026-07-12
- **Decision owners:** Research Lane™, Memory Lane™, Sentinel Lane™, Engineering Lane™

## Context

A fact without provenance, confidence, observation time, and verification history cannot be trusted as durable organizational intelligence.

## Decision

Every externally learned fact must carry Intelligence DNA™ throughout its lifecycle.

## Required DNA

- source and provenance;
- observation timestamp;
- observing agent;
- verifier;
- confidence;
- relationships;
- decisions influenced;
- agent usage;
- correction and confirmation history;
- retirement status.

## Consequences

### Positive

- Makes intelligence explainable and auditable.
- Supports correction, retirement, and confidence updates.
- Preserves how facts influenced organizational decisions.
- Enables trusted reuse across agents and Lanes.

### Tradeoffs

- Increases storage and schema complexity.
- Requires consistent identifiers across the pipeline.
- Incomplete DNA must prevent promotion into trusted knowledge.

