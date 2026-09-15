# FR-WP-06 — Model Governance and Assumption Register

## Classification rules
| Class | Meaning | Use |
|---|---|---|
| VCS | Verified current source input inherited from accepted research | May be modeled with source date; recheck if volatile |
| AUR | Accepted upstream research input | Planning/model input only |
| MPA | Modeled planning assumption | Sensitivity only; not fact |
| HODV | Human Owner decision variable | Never auto-select as approved |
| UPR | Unresolved/professional-review input | Placeholder/range only |

## Material input register
| Input | Treatment | Class | Status/control |
|---|---|---|---|
| KDP Amazon paperback payout | 50%/60% of list less print cost; 60% Amazon.com tier at $9.99+ | AUR/VCS | Volatile; live recheck before decision |
| KDP Expanded Distribution | 40% of list less print cost | AUR/VCS | Live recheck |
| KDP payment timing | ~60 days after month-end; Expanded ~90 days per accepted feeder | AUR/VCS | Cash sensitivity |
| Ingram compensation | list less wholesale discount, print cost, current fees | AUR/VCS | Live calculator/title capture required |
| Ingram wholesale discount | 55% accepted as current recommended trade-oriented reference; lower values sensitivity | AUR/HODV | No final discount approved |
| Ingram returns | No / Yes-Deliver / Yes-Destroy | AUR/HODV | No policy approved |
| Ingram U.S. Yes-Deliver handling | $3/returned book in accepted feeder | AUR/VCS | Recheck before implementation |
| Lulu Global Distribution | 50% channel share; creator 80% of gross profit after print/distribution | AUR/VCS | Recheck |
| Lulu bulk 100–499 | 5% automatic discount | AUR/VCS | Recheck |
| Return rate | low/base/high/stress variable | MPA/HODV | No universal rate asserted |
| List price | format/title-specific variable | HODV | No price approved |
| Author royalty basis/rate | configurable variable | HODV/UPR | Counsel/accounting/Human Owner required |
| Advance | $0/low/selective scenarios only | HODV | No advance approved |
| Title production budget | range/line-item model | MPA/HODV | Actual vendor/internal cost required |
| Direct processor/commerce fees | % + fixed fee variables | MPA/UPR | Provider validation required |
| Tax/GRT | explicit unresolved input | UPR | CPA review required |
| ISBN acquisition | block/quantity scenario only | UPR/HODV | Live Bowker capture before purchase |
| Rights/permissions | title-specific cost categories | UPR | Counsel/permissions quotes required |
| Lane C labor/vendor inputs | hours × loaded rate + vendors | MPA/UPR | FR-WP-04 refinement + actual costing |
| Sales volume/demand | downside/base/upside/stress | MPA | No demand forecast asserted |

## Freshness discipline
Accepted feeder retrieval dates: FR-WP-02 `2026-09-08`; FR-WP-03 `2026-09-10`. FR-WP-05 inputs require live Bowker/platform recheck at implementation. All platform/vendor economics are recheck-required before material commitments.

## Governance
Model outputs are analysis. Analysis may support recommendations. Recommendations require independent verification before PM acceptance. PM acceptance still does not equal Human Owner approval or execution authority.
