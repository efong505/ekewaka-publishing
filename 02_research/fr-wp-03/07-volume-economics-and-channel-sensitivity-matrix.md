# FR-WP-03 — Volume Economics and Channel Sensitivity Matrix

**Retrieval date:** 2026-09-10  
**Purpose:** Planning sensitivity only. Verified facts are labeled; otherwise entries are modeled operating posture.

## Verified public inputs used
- KDP Amazon print royalty: 50% or 60% of list less print cost; Amazon.com 60% paperback threshold begins at $9.99.
- KDP Expanded Distribution: 40% of list less print cost; paperback only.
- KDP example 300-page U.S. black-ink paperback print cost: $4.60.
- Lulu: no minimum order; 100–499 copies receive 5% bulk discount; 500+ custom quote.
- 48 Hour Books: 10-copy minimum; 100+ gets 25 additional books; current price breaks at 500/1,000/2,500/5,000; cited 100-order/125-delivered example effective $4.74 each for a 6×9 180-page B&W paperback.
- Bookmobile: 25-copy minimum for short-run work.
- PrintNinja: 250-copy minimum for cited hardcover/art-book offset products.

## Representative KDP sensitivity — illustration only
Assumptions: U.S. 300-page regular-trim black-ink paperback, $4.60 print cost, modeled $15.99 list.

| Channel | Formula | Approx. publisher receipt/unit |
|---|---|---:|
| KDP Amazon.com | 0.60 × 15.99 − 4.60 | $4.99 |
| KDP Expanded Distribution | 0.40 × 15.99 − 4.60 | $1.80 |

Because KDP retail POD is per-copy, multiplying units scales gross publisher receipts approximately linearly before other title expenses. This is **not** evidence that KDP is cheapest for a publisher-owned bulk order.

## Quantity matrix
| Quantity | POD posture | Short-run posture | Offset posture | Inventory / cash exposure | Required comparison before decision |
|---:|---|---|---|---|---|
| 1 | Preferred for proof/uncertain demand | Usually uneconomic / below vendor minimum | Not viable | Minimal | KDP vs Ingram/Lulu proof landed cost |
| 10 | Strong | 48 Hour Books minimum becomes available | Not viable | Low | POD author copies vs 10-copy quote |
| 25 | Strong | Bookmobile minimum and local digital become relevant | Usually not viable | Low/moderate | KDP/Ingram/Lulu landed vs Bookmobile/local |
| 50 | Strong for uncertainty | Increasingly credible for events/institutional order | Usually not first choice | Moderate | At least 2 short-run quotes if demand known |
| 100 | Still viable | Strong comparison point; Lulu 5% bulk discount; 48HB 25-extra-copy incentive | Some offset vendors may still be below minimum | Moderate | POD vs local/national short-run landed cost |
| 250 | Viable but likely higher manufacturing/unit | Strong | First serious offset comparison; PrintNinja cited minimum | Moderate/high | Short-run + offset + freight/storage |
| 500 | Viable for zero inventory | Strong with volume breaks | Strong candidate | High | Formal digital vs offset landed-cost comparison |
| 1,000 | Operationally simple but unit cost may be high | Possible | Often economically attractive if demand proven | High | Offset quotes + warehouse/3PL + sell-through stress test |
| 5,000+ | Useful only for demand uncertainty/backlist continuity | Usually not preferred as primary manufacturing method | Primary large-run candidate | Very high | Human Owner gate; multiple offset quotes; freight, storage, shrink, insurance, cash conversion |

## Landed-cost normalization
Every quantity comparison must use:

`manufacturing + setup/prepress + proofs + freight + receiving + storage + pick/pack + outbound shipping subsidy + damage/shrink + inventory financing/carrying cost`

For direct sales, add payment processing, ecommerce/platform charges, refunds/chargebacks and customer support. For trade, add wholesale discount, distributor/platform fees and returns reserve.

## Channel sensitivity set for FR-WP-06
1. Amazon-heavy POD.
2. Ingram trade-heavy at trade-friendly discount/returnability.
3. Ingram lower-discount/nonreturnable margin-preservation case.
4. Direct POD via Lulu Direct.
5. Direct stocked short-run inventory.
6. Event/church/institutional bulk with customer-paid freight.
7. Event/church/institutional bulk with publisher-subsidized freight.
8. Offset inventory at 500/1,000/5,000 with low/base/high sell-through.

## Breakpoint principle
No universal quantity breakpoint is adopted. The correct breakpoint is where **landed unit cost + risk-adjusted carrying cost + expected unsold/return cost** becomes lower than the alternative while still satisfying quality, timing and channel requirements.
