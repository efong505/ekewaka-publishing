# FR-WP-06 — Lane C Author-Services Cost Model

**Purpose:** cost architecture only. Lane C is not launched and no public price/package is approved.

## Cost stack
`Direct labor = Σ(hours_skill × loaded_rate_skill)`.
`Contractor cost = Σ(per-word/per-hour/per-project vendor cost)`.
`PM/QA cost = PM hours + QA/rework allowance`.
`Delivery cost = labor + contractors + software/licenses + included-copy landed cost + support + variable admin + refund/chargeback expected loss`.

If a target gross-margin floor `g` and processor rate `p` are later approved, a mechanical price-floor check can use:
`Price floor = (Delivery cost + fixed per-transaction fees) / (1 − p − g)`.
This is a formula, not an approved target margin or price.

## Sensitivities
- estimated hours;
- +20% and +50% labor overrun;
- contractor cost inflation;
- revision rounds;
- change-order realization;
- customer-support burden;
- included-copy and shipping cost;
- payment fees;
- refunds/chargebacks;
- tax/GRT treatment.

## FR-WP-04 dependency
FR-WP-04 must still refine competitive package scope, market benchmark context, customer expectations, and comparable service structures before any public Lane C packaging/pricing decision. FR-WP-06 does not substitute for that work.

## Gate
Actual loaded labor rates, vendor quotes, tax/GRT, processor costs, refund policy, scope language, and margin target must be validated/approved through later stages.
