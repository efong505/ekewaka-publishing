# FR-WP-06 — Lane A Title Economics Model

## Title P&L architecture
### Revenue variables
`LP_f` list price by format; `Mix_c` units by channel; `NetRev_c` channel-specific publisher cash revenue; subsidiary/translation/audio revenue modules default to zero unless rights and terms support them.

### Variable cost variables
Manufacturing, retailer/distributor deductions, wholesale discount, returns/chargebacks, return handling, shipping/freight/fulfillment, payment fees, author royalty, author-copy cost, metadata/relisting, permissions, and title-specific variable support.

### Fixed/title-development variables
Developmental/line/copy edit, proofread, cover, interior, conversion, project management, legal/sensitivity/fact review, metadata setup, proof/ARC costs, initial marketing allocation, rights/permissions setup, and overhead allocation.

## Core formulas
- `Net contribution/unit_c = NetRev_c − Print_c − Fulfillment_c − ExpectedReturnCost_c − Royalty_c − OtherVariable_c`.
- `Weighted contribution/unit = Σ(Mix_c × contribution_c)`.
- `Break-even gross units = FixedTitleInvestment / WeightedContribution`, if positive.
- `Cash-at-risk = prepaid fixed title cost + prepaid inventory/freight + unreleased return reserve + committed marketing + contingent title-specific costs`.

## Royalty sensitivity
Royalty is not approved. Model it by explicit basis and rate: `Royalty = RoyaltyBasis × R`. Test at least `R=0%`, a low planning case, and a higher case; the basis must be identified (list, net receipts, or another contract-defined basis). No contract term is inferred from benchmark evidence.

## Illustrative reference case
Synthetic $18.99 paperback, KDP 60% payout and $4.60 accepted KDP benchmark print cost gives $6.79 pre-royalty contribution. With a modeled 10% royalty on KDP publisher receipts (`$11.394 × 10%`), illustrative contribution becomes about `$5.65` before allocated overhead and title fixed cost.

## Acquisition/underwriting control
The model can show a break-even range but cannot establish an acquisition threshold, offer, advance, royalty, or final title budget. Those remain Human Owner-gated and, where relevant, counsel/accounting-reviewed.
