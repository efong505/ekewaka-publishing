# FR-WP-03 — FR-WP-06 Financial-Model Input Register

**Retrieval date:** 2026-09-10  
**Purpose:** Traceable input register only. FR-WP-06 remains separate and must not be finalized here.

## Input classes
- **VERIFIED CURRENT** — current primary vendor/platform source.
- **BENCHMARK** — public example, not a title-specific Ekewaka quote.
- **SENSITIVITY** — variable FR-WP-06 must test.
- **VENDOR VALIDATION** — live quote/account calculator required before hard-coding.
- **PROFESSIONAL REVIEW** — CPA/legal/commerce review required.

## A. KDP inputs
| Input | Value / treatment | Class |
|---|---|---|
| Amazon print payout | 50% or 60% of list less print cost | VERIFIED CURRENT |
| Amazon.com paperback 60% threshold | $9.99+ | VERIFIED CURRENT |
| Expanded Distribution payout | 40% of list less print cost | VERIFIED CURRENT |
| Expanded Distribution hardcover | Not eligible | VERIFIED CURRENT |
| 300-page U.S. B&W example print cost | $4.60 in KDP example | BENCHMARK |
| Standard payment timing | ~60 days after month-end | VERIFIED CURRENT |
| Expanded cash timing | materially later; KDP pricing page states ~90 days after month-end | VERIFIED CURRENT |
| Author-copy landed cost | print + destination shipping/tax | VENDOR VALIDATION |

## B. Ingram inputs
| Input | Value / treatment | Class |
|---|---|---|
| Compensation structure | list − wholesale discount − print cost − applicable current fees | VERIFIED CURRENT |
| Trade-oriented wholesale discount | 55% commonly recommended by Ingram | VERIFIED CURRENT / SENSITIVITY |
| Lower discount | test lower values supported by account/market | SENSITIVITY |
| Returns | No / Yes-Deliver / Yes-Destroy | VERIFIED CURRENT |
| Return chargeback | current wholesale cost | VERIFIED CURRENT |
| Yes-Deliver U.S. handling | $3 per returned book | VERIFIED CURRENT |
| Yes-Deliver non-U.S. handling | $20 per returned book | VERIFIED CURRENT |
| Yes-Destroy handling | no return shipping/handling, wholesale cost still charged | VERIFIED CURRENT |
| Print cost / market-access fee | title/spec dependent | VENDOR VALIDATION |
| Publisher-order shipping | quantity/location/destination dependent | VENDOR VALIDATION |

## C. Lulu inputs
| Input | Value / treatment | Class |
|---|---|---|
| Global Distribution channel share | 50% of retail price to distribution channels | VERIFIED CURRENT |
| Gross-profit split | creator 80% / Lulu 20% after print and distribution fees | VERIFIED CURRENT |
| Direct transaction structure | merchant sale + separate Lulu fulfillment transaction | VERIFIED CURRENT |
| Direct print/ship cost | title/destination dependent | VENDOR VALIDATION |
| Bulk 100–499 | 5% automatic discount | VERIFIED CURRENT |
| Bulk 500+ | custom quote | VERIFIED CURRENT |
| Direct payment processing | Stripe/store/platform dependent | SENSITIVITY / VENDOR VALIDATION |
| Tax/GRT allocation | implementation specific | PROFESSIONAL REVIEW |

## D. Short-run / offset inputs
| Input | Value / treatment | Class |
|---|---|---|
| 48 Hour Books minimum | 10 | VERIFIED CURRENT |
| 48HB 100+ incentive | 25 additional copies | VERIFIED CURRENT |
| 48HB 100-order example | 125 total, 6×9 180pp B&W, effective $4.74 each | BENCHMARK |
| 48HB price-break quantities | 500 / 1,000 / 2,500 / 5,000 | VERIFIED CURRENT |
| Bookmobile minimum | 25 | VERIFIED CURRENT |
| PrintNinja cited offset minimum | 250 for hardcover/art-book products | VERIFIED CURRENT |
| Offset production lead | spec/vendor dependent; cited PrintNinja HC 4–6 weeks + freight transit | BENCHMARK / VENDOR VALIDATION |
| Local NM print cost | quote required | VENDOR VALIDATION |
| Freight/pallet | quote required | VENDOR VALIDATION |
| Warehousing | $/pallet or $/unit/month later | VENDOR VALIDATION |

## E. Direct fulfillment inputs
FR-WP-06 must provide fields for:
- payment percentage + fixed fee;
- ecommerce platform fee;
- print/manufacturing;
- fulfillment/pick-pack;
- packaging;
- postage/freight;
- customer-paid vs publisher-subsidized shipping;
- refunds/returns;
- chargebacks/fraud;
- customer support;
- sales tax/GRT treatment;
- warehouse receiving/storage;
- shrink/damage;
- inventory carrying/financing cost.

## F. Trade return-reserve inputs
Do not hard-code a universal return rate. Model low/base/high by title/channel using:
- gross trade units;
- wholesale value/unit;
- return-rate sensitivity;
- return timing lag;
- return method;
- handling/shipping;
- reserve additions/releases.

## G. Author-copy economics
Model separately:
- contractual free copies, if later adopted;
- extra author copies at print/discounted price;
- freight/tax;
- publisher administrative handling if any;
- whether author copies are royalty-bearing or excluded, to be decided later by contract/accounting work.

## H. Required volume scenarios
`1 / 10 / 25 / 50 / 100 / 250 / 500 / 1,000 / 5,000+`

For each, compare at minimum:
- POD landed cost;
- short-run landed cost where supported;
- offset landed cost where supported;
- inventory cash committed;
- expected unsold units;
- storage/fulfillment;
- contribution by direct vs trade channel.

## I. Cash-conversion fields
- order/sale date;
- manufacturing payment date;
- freight payment date;
- inventory receipt date;
- retailer/distributor reporting date;
- publisher cash receipt date;
- return charge date;
- reserve release date;
- author royalty accrual/payment date.

## J. Hard gate before FR-WP-06 finalization
Current live quotes/calculator captures are required for representative Ekewaka title specifications from KDP, Ingram, Lulu, and at least two short-run/offset candidates. FR-WP-05 ISBN/metadata dependencies must also be sufficiently mature.