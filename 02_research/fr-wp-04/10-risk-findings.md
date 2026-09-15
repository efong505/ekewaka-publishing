# FR-WP-04 — Risk Findings

**Retrieval date:** 2026-09-15

## Governing risks preserved

| Risk | Severity | FR-WP-04 implication |
|---|---:|---|
| RISK-002 — Trade/services/hybrid confusion | Critical | Lane C contracts, onboarding, marketing, ISBNs/accounts and accounting must remain visibly separate from Lane A and any future Lane B. |
| RISK-008 — Service-package underpricing | High | Bottom-up labor/vendor costing, scope ceilings, PM/QA, revision controls and margin testing are mandatory before pricing. |
| RISK-009 — Misleading author-service marketing | Critical | Sell defined work; never imply acquisition, guaranteed sales, reviews, bestseller status or bookstore/library placement. |
| RISK-014 — Excessive operational complexity | Medium/High | Too many bespoke combinations, formats, websites, marketing assets and revision paths can overwhelm capacity. |
| RISK-015 — Vendor/platform dependency | Medium/High | Preserve customer account/file portability and avoid provider-controlled identifiers where unnecessary. |

## FR-WP-04-specific findings

### SERV-R01 — Editorial scope ambiguity
**Severity:** High  
A label such as "editing included" can conceal materially different developmental/copy/proof labor. Word count, editorial level, manuscript condition and passes must be explicit.

### SERV-R02 — Revision leakage / post-approval rework
**Severity:** High  
Unlimited or undefined revisions can erase contribution margin. Provider-error corrections and customer-requested changes require separate treatment.

### SERV-R03 — Public pricing volatility / inconsistency
**Severity:** Medium/High  
Provider package prices can change or conflict across pages. Destiny House currently demonstrates a material homepage/product-page inconsistency. Live recheck is required before material pricing decisions.

### SERV-R04 — ISBN / publisher-of-record ambiguity
**Severity:** High  
A customer may retain rights yet still be tied to a provider-supplied ISBN/imprint or provider-listed publisher identity. Lane C must explicitly control each field.

### SERV-R05 — Account/control lock-in
**Severity:** High  
Provider-controlled publishing/distribution accounts can complicate migration, revenue visibility and offboarding. Customer-owned accounts are preferred where practicable.

### SERV-R06 — Marketing expectation inflation
**Severity:** Critical  
Bundled "marketing" can create expectations of press pickup, reviews, ranking or sales. Deliverables and outcome exclusions must be explicit.

### SERV-R07 — Refund/chargeback/installment exposure
**Severity:** Medium/High  
Long projects, subjective creative approvals and installment billing create collection/refund/dispute risk. Policy, accounting and processor controls require later validation.

### SERV-R08 — Capacity compression
**Severity:** High  
Editing-heavy projects can consume dozens of labor hours each before design/PM. Concurrent intake without utilization controls can create delays, rushed QA and margin loss.

## Risk treatment posture

FR-WP-04 does not close these risks. It provides controls and variables for Phase 4 service/package architecture, FR-WP-06 refinement, professional review and Human Owner decisions.
