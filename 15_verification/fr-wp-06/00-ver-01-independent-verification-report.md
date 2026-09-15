# FR-WP-06 — VER-01 Independent Verification Report

**Verifier:** VER-01 — Independent Review / Verification Agent  
**Repository:** `efong505/ekewaka-publishing`  
**Branch:** `main`  
**VER-01 starting baseline:** `71fb48964869bde1989d1d701a1eb203cb3c9a78`  
**Completed FIN-01 package baseline:** `b4717144d7c9e3dfe424c3c6bf382545c2478351`  
**Verification date:** 2026-09-15  
**Disposition:** **Verified With Conditions**

> Commit-record note: the exact final repository commit for this verification is the commit that records the corresponding FR-WP-06 verification disposition in `00_governance/work-package-register.md`; the executing completion report must return that exact SHA. This avoids an impossible self-referential commit hash inside the report content.

## 1. Preliminary governance and ancestry checks

Repository identity and branch were independently confirmed as `efong505/ekewaka-publishing` / `main`. The starting HEAD was `71fb48964869bde1989d1d701a1eb203cb3c9a78`.

Comparison of completed FIN-01 baseline `b4717144d7c9e3dfe424c3c6bf382545c2478351` to the VER-01 starting baseline found exactly two later commits affecting only:

- `18_handoffs/fr-wp-06-ver-01-independent-verification-launcher.md`; and
- `00_governance/work-package-register.md` for routing state.

No post-FIN-01 commit changed the model artifacts, model assumptions, arithmetic, or authorized FIN-01 scope before verification began.

The governing launcher, current work-package register, Human Owner gates, risk register, FIN-01/VER-01 role boundaries, accepted FR-WP-02/03/05 feeder conditions, and all FR-WP-06 artifacts `00` through `14` were reviewed.

## 2. Package-completeness result

**PASS WITH CONDITIONS.**

All required governed Markdown artifacts exist under `02_research/fr-wp-06/`:

`00-main-financial-model-report.md` through `14-evidence-and-assumption-source-register.md`.

FR-WP-06 was correctly left at execution complete / review pending before VER-01 action. FIN-01 did not claim Verified, PM Accepted, Human Owner Approved, Final Financial Model, Final Pricing Approved, Production Ready, or Commercially Approved. FR-WP-04 remains separately PLANNED.

Two documentation/auditability conditions are recorded below; neither invalidates the bounded model architecture.

## 3. Independent external evidence recheck

VER-01 independently rechecked the principal volatile platform mechanics against current primary/provider sources on 2026-09-15.

### KDP
Current KDP guidance confirms:

- paperback Amazon marketplace royalties use 50% or 60% of list price depending on marketplace/list-price tier, less printing cost;
- Amazon.com reaches the 60% paperback tier at USD 9.99+;
- Expanded Distribution uses 40% of list price less printing cost;
- Expanded Distribution is not available for hardcover;
- current payment timing is approximately 60 days after month-end for standard distribution and approximately 90 days for Expanded Distribution;
- KDP's current 300-page black-ink U.S. paperback example calculates to `$4.60` printing cost.

Primary sources rechecked:

- https://kdp.amazon.com/en_US/help/topic/G201834330
- https://kdp.amazon.com/en_US/help/topic/G8BKPU9AGVZSF9QF
- https://kdp.amazon.com/en_US/help/topic/GK2MKZUL6U3SFBPZ

### IngramSpark
Current IngramSpark material supports:

- wholesale discount as a publisher-controlled input;
- a current broad trade-oriented recommendation/range around 53%–55%, making 55% a valid planning sensitivity rather than a mandatory universal value;
- returnability choices including No / Yes-Deliver / Yes-Destroy;
- Yes-Deliver return exposure at current wholesale cost plus current U.S. `$3` per-book handling and current international `$20` handling;
- Yes-Destroy still exposes the publisher to current wholesale cost without return shipping/handling.

Primary/provider sources rechecked:

- https://www.ingramspark.com/hubfs/downloads/user-guide.pdf
- https://www.ingramspark.com/blog/how-to-set-up-a-title-with-ingramspark-part-1

### Lulu
Current Lulu guidance confirms:

- Global Distribution print distribution fees consume 50% of retail/gross revenue;
- Gross Profit is the remainder after print cost and distribution fees;
- Lulu's print share is 20% of Gross Profit and creator revenue is 80% of Gross Profit.

Primary source rechecked:

- https://help.lulu.com/en/support/solutions/articles/64000255464-creator-revenue-the-basics

**Evidence result:** the key current platform mechanics inherited by FIN-01 remain materially supported. Volatile-value live-recheck controls remain necessary and were correctly preserved.

## 4. Source/provenance result

**PASS WITH CONDITION VER06-C2.**

The source register traces material categories to the FIN-01 launcher, governance, accepted feeder acceptance records, and the FR-WP-02/03/05 FR-WP-06 input registers. Modeled values are separately listed as MPA/HODV rather than represented as source facts.

The package preserves retrieval dates for FR-WP-02 (`2026-09-08`) and FR-WP-03 (`2026-09-10`) and explicitly requires live rechecks for volatile vendor/platform economics.

The current Ingram 55% example remains acceptable as a modeled trade-oriented sensitivity, but later decision use should preserve the current-source nuance that Ingram guidance also identifies approximately 53%–55% as a broad trade-oriented range rather than treating 55% as a universally required value.

## 5. Assumption-governance result

**PASS.**

FIN-01 distinguishes:

- VCS — verified current source input inherited from accepted research;
- AUR — accepted upstream research;
- MPA — modeled planning assumption;
- HODV — Human Owner decision variable;
- UPR — unresolved/professional-review input.

List price, royalty basis/rate, return rate, title budget, direct-commerce fees, taxes/GRT, ISBN purchase economics, rights/permissions, Lane C costs, and sales demand remain appropriately non-final.

## 6. Arithmetic/formula verification

**PASS WITH CONDITION VER06-C1.**

VER-01 independently recalculated the headline arithmetic.

### Channel examples
Using synthetic list price `$18.99` and synthetic/common `$4.60` manufacturing where stated:

- KDP 60%: `18.99 × 0.60 − 4.60 = 6.794`, reported `$6.79` — correct.
- KDP Expanded: `18.99 × 0.40 − 4.60 = 2.996`, reported `$3.00` — correct.
- Ingram-style 55% discount: `18.99 × 0.45 − 4.60 = 3.9455`, reported `$3.95` before returns/fees — correct.
- Lulu Global: `(18.99 × 0.50 − 4.60) × 0.80 = 3.916`, reported `$3.92` — correct.
- Synthetic direct: `18.99 − 4.60 − (18.99×0.03+0.30) − 2.50 = 11.0203`, reported `$11.02` before royalty/refunds/tax/shipping subsidy/overhead — correct.

### Base weighted contribution reconstruction
The exact reported base value `$5.250146` is mathematically reproducible using a coherent interpretation of the stated model variables:

- KDP contribution after 10% royalty on KDP publisher receipts: `$5.6546`;
- Ingram-style contribution after a 15% wholesale-receipt return chargeback and 10% royalty on post-return publisher net receipts, with no Yes-Deliver handling amount included in this base arithmetic: `$1.9373075`;
- Direct contribution after processor cost and 10% royalty on publisher receipts net of processor, before the other unresolved direct liabilities: `$9.20827`;
- weighted result: `0.50×5.6546 + 0.30×1.9373075 + 0.20×9.20827 = 5.25014625`.

Thus `$8,000 / $5.250146 ≈ 1,523.77`, correctly reported as approximately **1,524 gross units**.

However, the FIN-01 package does not itself spell out those exact per-channel royalty bases and the base-case decision to exclude Yes-Deliver handling from the weighted demonstration. Because royalty basis and return handling materially affect contribution, this is an auditability/documentation condition rather than an arithmetic failure.

### Other headline scenarios
- Downside: `$12,000 / $1.75 = 6,857.14` → approximately **6,858** units — correct conservative whole-unit rounding.
- Upside: `$5,000 / $8.00 = 625` — correct.
- Stress: `$12,000 / $0.50 = 24,000` — correct.

### Company-level mechanical examples
- `$12,000 / 15% = $80,000` — correct.
- `$36,000 / 30% = $120,000` — correct.
- `$72,000 / 45% = $160,000` — correct.

No evidence of double-counting was found in the stated formulas, but future populated models must continue testing for overlaps between return reserves, inventory reserves, title cash-at-risk, and contingent reserves.

## 7. Lane A / title-economics result

**PASS WITH VER06-C1.**

The model separately surfaces revenue/channel mix, manufacturing, distribution deductions, returns, shipping/fulfillment, editorial/production/project-management investment, marketing, ISBN/metadata/rights administration, counsel/permissions, royalty variables, advances, contribution, break-even, cash-at-risk, and timing.

Royalty and advance economics are explicitly scenario variables only. No acquisition threshold or final title budget is approved.

## 8. Channel-unit-economics result

**PASS.**

KDP Amazon POD, KDP Expanded, Ingram trade/POD, Lulu Global, direct POD, stocked direct inventory, events/churches/institutions/bulk, and short-run/offset channels remain distinct. The package correctly refuses to claim decision-grade short-run/offset economics without comparable quotes, freight, storage, and fulfillment evidence.

## 9. Returns/inventory/cash result

**PASS WITH VER06-C1.**

Return rate remains a sensitivity, not a fact. Wholesale-value chargebacks, handling/shipping, carrying cost, storage, shrink/damage/obsolescence, freight, receivable timing, reserve addition/release, and inventory cash commitment are represented.

The structural model is correct. The base demonstration should explicitly identify its assumed return method/handling treatment so an independent reviewer need not infer why the `$5.250146` calculation omits Yes-Deliver handling.

## 10. Lane B research-only result

**PASS.**

Lane B remains research-only. No program launch, fee, package, promise, royalty/revenue-share term, or offer was approved. Publisher/author contribution, production, obligations, refund/cancellation, returns, sales realization, break-even, exposure, and reputational/segregation controls are represented as sensitivities.

## 11. Lane C cost-model result

**PASS.**

Lane C is a bottom-up cost architecture, not public pricing. Labor, contractor/vendor cost, PM/QA, complexity, revision/rework, scope changes, payment processing, refunds/chargebacks, support, tax/GRT, margin mechanics, and service capacity are represented.

FR-WP-04 is explicitly retained as a required future refinement before any public package/pricing decision.

## 12. ISBN / metadata / rights-cost result

**PASS.**

The model uses FR-WP-05 as planning architecture only. Live Bowker choices, identifier consumption, metadata labor/reconciliation, migration, founding-catalog provenance, counsel/permissions, rights/royalty variables, account control, registry/audit infrastructure, and reversion/wind-down remain non-final or unresolved.

No ISBN purchase/assignment, final publisher-of-record architecture, rights valuation, royalty, territory, term, or reversion term was approved.

## 13. Company-level model result

**PASS.**

The structure distinguishes fixed/recurring, variable, and one-time/contingent categories; uses cash-flow rather than accounting-profit-only logic; carries receivable timing; includes break-even mechanics and capacity constraints; and labels all numerical company examples as synthetic planning placeholders.

No unsupported salary, rent, insurance premium, tax treatment, vendor contract, or demand forecast is presented as a settled fact.

## 14. Scenario/stress-test result

**PASS.**

Downside, base/planning, upside, and stress cases exist, with explicit sensitivity dimensions for returns, manufacturing inflation, wholesale discount, direct-channel mix, processor/fulfillment cost, title investment, royalty, volume, delayed receivables, refunds/chargebacks, inventory sell-through, and labor/contractor overrun.

The scenarios are planning sensitivities, not forecasts.

## 15. Break-even/margin/reserve result

**PASS WITH VER06-C1.**

Headline break-even arithmetic is correct. Reserve formulas appropriately keep operating, returns, inventory, title pipeline, and professional/contingent exposures separate and prohibit approval of a reserve amount or months-of-cover target.

The exact base-case component arithmetic should be made explicit before downstream PM reliance as described in VER06-C1.

## 16. Findings confirmed

VER-01 confirms that:

1. channel mix is a first-order economic driver;
2. trade returns can materially impair thin wholesale contribution;
3. production investment and author economics materially drive Lane A break-even;
4. Lane B remains a segregated research-only framework;
5. Lane C needs bottom-up costing plus FR-WP-04 market refinement before public pricing;
6. ISBN/metadata/rights costs should remain parameterized pending live/professional inputs;
7. company liquidity must account for cash timing and downside exposure;
8. volatile platform/vendor terms require live recheck before material decisions.

## 17. Findings challenged / conditions

### VER06-C1 — Base-case calculation trace
**Severity:** nonblocking verification condition.  
**Issue:** the exact `$5.250146` weighted contribution is reproducible, but the package does not explicitly show the per-channel royalty bases and return-method/handling assumption used in the base computation.  
**Required downstream control:** before PM acceptance relies on the headline base scenario, add or preserve an explicit calculation trace identifying royalty basis by channel and whether the trade-return example assumes Yes-Destroy/no-return-handling, Yes-Deliver, or another handling treatment. Any Yes-Deliver sensitivity must include applicable handling.

### VER06-C2 — Risk coverage and Ingram wording
**Severity:** nonblocking verification condition.  
**Issue:** `12-risk-findings.md` does not explicitly list active `RISK-013` (AI/content-rights disputes) or `RISK-014` (operational complexity), both of which the VER-01 launcher required to be independently assessed. Also, current Ingram material supports a broader approximately 53%–55% trade-oriented range, while the model uses 55% as its reference scenario.  
**Required downstream control:** carry `RISK-013` and `RISK-014` forward explicitly in the PM record or bounded documentation correction, and ensure 55% remains a sensitivity/reference rather than a universal requirement.

Neither condition changes the mathematical viability of the bounded model architecture or authorizes FIN-01 to revise its own package during independent verification.

## 18. Material risks and status

VER-01 independently assessed the launcher-required risk set:

- `RISK-002` lane confusion — remains active; no status change.
- `RISK-003` unsustainable trade-title economics — remains Critical; no status change.
- `RISK-004` defective rights/royalty terms — remains Critical; no status change.
- `RISK-005` incorrect royalty accounting — remains Critical; no status change.
- `RISK-006` ISBN provenance errors — remains High; no status change.
- `RISK-007` distributor/returns exposure — remains High; no status change.
- `RISK-008` service-package underpricing — remains High; no status change.
- `RISK-009` misleading author-service marketing — remains Critical; no status change.
- `RISK-010` cash-flow strain — remains High; no status change.
- `RISK-011` premature outside-author acquisition — remains Critical; no status change.
- `RISK-013` AI/content-rights disputes — remains High; no status change; explicit FR-WP-06 risk-artifact carry-forward condition VER06-C2 applies.
- `RISK-014` operational complexity — remains Medium/High; no status change; explicit FR-WP-06 risk-artifact carry-forward condition VER06-C2 applies.
- `RISK-015` vendor/platform dependency — remains Medium/High; no status change.
- `RISK-016` conflicting project documentation — remains High; no status change.

No risk is closed, downgraded, or accepted by VER-01.

## 19. Unresolved professional / implementation inputs

The following remain open and are not silently resolved:

- CPA/tax/GRT review;
- publishing/IP counsel review;
- live KDP/Ingram/Lulu landed-cost captures;
- comparable short-run/offset vendor quotes;
- freight, warehouse and 3PL validation;
- evidence-backed return-rate calibration;
- live Bowker pricing/options;
- platform/account behavior, ownership and recovery;
- founding-catalog provenance;
- ISBN/metadata/rights registry and audit controls;
- title-specific chain-of-title and permissions;
- actual labor/contractor costs;
- payment/ecommerce costs;
- insurance/accounting/admin costs;
- actual market demand and channel mix.

## 20. FR-WP-04 dependencies/refinements

FR-WP-04 remains **PLANNED**. It remains required to refine competitive author-services package scope, market benchmark context, customer expectations, and comparable service structures before Lane C public packaging/pricing decisions.

FR-WP-06 does not substitute for FR-WP-04.

## 21. Human Owner gate verification

**PASS.**

FIN-01 did not approve or execute final prices, wholesale discounts, returns policy, royalties, advances, acquisitions, author-service pricing, reserves/cash commitments, vendor selections, procurement, ISBN purchases/assignments, contracts, rights acquisition/transfer, tax/legal/entity/accounting determinations, Lane B/Lane C launch, outside-author publishing, payment/royalty/accounting deployment, paid marketing, production/publication decisions, or unauthorized outreach.

Edward Fong remains the Human Owner and final decision authority.

## 22. Readiness for PM-01 acceptance

**YES — READY FOR PM-01 ACCEPTANCE REVIEW WITH NONBLOCKING CONDITIONS VER06-C1 AND VER06-C2.**

This finding does not itself constitute PM acceptance. PM-01 should independently determine whether to accept the verified package with conditions, require a bounded documentation correction before acceptance, or take another governed action.

## 23. Exact recommended PM next action

**Route FR-WP-06 — Verified With Conditions to PM-01 for Research Acceptance / Governance Decision, preserving VER06-C1, VER06-C2, all open professional/implementation-validation items, FR-WP-04 dependencies, active risks, and Human Owner gates.**

## 24. VER-01 disposition

**Verified With Conditions**
