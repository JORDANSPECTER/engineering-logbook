# ADR-007: Organizational Significance Governs Graph Node Creation

- **Status:** Accepted
- **Date:** 2026-07-12
- **Decision owners:** Founder, Memory Lane™, Engineering Lane™

## Context

Creating a graph node for every collected detail would cause node explosion, reduce navigability, and make the Organization Graph less meaningful.

## Decision

Knowledge becomes an Organization Graph node only when it has organizational significance. Useful supporting information remains evidence attached to an existing node or is stored in Memory Foundry. Trivial or low-value information is ignored.

## Consequences

### Positive

- Keeps the graph understandable and strategically useful.
- Reduces duplicate and low-value nodes.
- Preserves evidence without distorting organizational structure.
- Improves graph performance and governance.

### Tradeoffs

- Significance rules require explicit policy and review.
- Borderline cases may be classified differently by agents.
- Evidence attachment must remain searchable.

## Evaluation criteria

A proposed node should represent at least one of the following:

- a durable organizational entity;
- an accountable owner or authority;
- a mission, decision, policy, risk, product, or governed asset;
- a relationship that materially affects operations;
- intelligence likely to influence future decisions.

