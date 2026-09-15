# FR-WP-06 — Break-Even, Margin and Reserve Analysis

## Title break-even
`BE_units = FixedTitleInvestment / WeightedUnitContribution`.
If contribution is zero or negative, there is no finite operating break-even under that scenario; assumptions or business structure must change.

Reference planning case: `$8,000 / $5.250146 ≈ 1,524` gross units. This is illustrative only.

## Sensitivity priorities
1. channel mix/direct share;
2. return rate and wholesale discount;
3. manufacturing/landed cost;
4. royalty basis/rate;
5. fixed production investment;
6. fulfillment/payment/support burden;
7. discounting/refunds.

## Margin guardrails for later decision
The model should report contribution dollars and margin percentage by channel and title, but FIN-01 does not set a minimum approved margin.

## Reserve mechanics
- `Operating reserve = monthly fixed cash burn × months-of-cover decision variable`.
- `Return reserve = exposed trade receipts × modeled return sensitivity + handling/freight exposure`.
- `Inventory reserve = unsold-at-risk landed inventory + shrink/damage/obsolescence sensitivity`.
- `Title pipeline reserve = committed unpaid title-development and launch obligations`.
- `Professional/contingent reserve = unresolved counsel/CPA/permissions/implementation exposures`.

`Minimum cash reserve scenario = operating + returns + inventory + pipeline + professional/contingent reserves − specifically segregated non-overlapping amounts`.

No reserve amount or months-of-cover target is approved by this package.
