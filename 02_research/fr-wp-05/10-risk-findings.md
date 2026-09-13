# FR-WP-05 — Risk Findings

## Existing risks materially engaged
- **RISK-002 — Trade/services/hybrid confusion (Critical):** publisher-of-record, ISBN ownership and rights grants can blur lanes if not explicitly separated.
- **RISK-004 — Defective rights/royalty terms (Critical):** foundational rights categories are identified, but final language and economic terms require qualified counsel and later Human Owner approval.
- **RISK-006 — ISBN ownership/provenance errors (High):** platform-provided identifiers, prior-title migrations and edition changes can create incorrect publisher identity or duplicate/conflicting records.
- **RISK-011 — Premature outside-author acquisition (Critical):** no outside-author publication should occur before rights-chain, contract, ISBN, metadata and accounting controls are operational.
- **RISK-013 — AI/content-rights disputes (High):** AI-assisted text, artwork and synthetic voice can create ownership, warranty, permission and training-use questions requiring explicit policy/contract treatment.
- **RISK-015 — Vendor/platform dependency (Medium/High):** free platform ISBNs and platform-controlled bibliographic feeds increase switching friction.
- **RISK-016 — Conflicting project documentation (High):** canonical identifier/metadata/rights registries are needed to prevent conflicting title states.

## Additional FR-WP-05 risk findings
**FR05-R1 — Metadata divergence (High):** canonical publisher metadata may differ from Bowker, distributor and retailer display data. Control: per-channel observed-state reconciliation and exception queue.

**FR05-R2 — Identifier overconsumption/underplanning (Medium):** format growth and revised editions can consume ISBN inventory faster than title count suggests. Control: per-format/edition forecasting.

**FR05-R3 — Accidental publisher-role transfer (High):** selecting a free platform ISBN can cause platform/imprint publisher identity in bibliographic records. Control: explicit identifier decision gate.

**FR05-R4 — Rights-scope ambiguity (Critical):** operational teams may assume rights not expressly granted. Control: rights registry with positive rights-granted/retained fields and contract reference.

**FR05-R5 — Reversion wind-down failure (High):** rights may revert while listings, files or metadata remain active. Control: contract-linked offboarding checklist, inventory/status handling and channel withdrawal tracking.

## Risk disposition
No project risk is closed, downgraded or accepted by RIGHTS-01. Risk ownership and any status change remain with PM-01/Human Owner under project governance.