# FR-WP-03 — VER-01 Independent Verification Report

**Work package:** FR-WP-03 — Printing, Distribution & Fulfillment Baseline  
**Verifier:** VER-01 — Independent Review / Verification Agent  
**Human Owner:** Edward Fong  
**Repository:** `efong505/ekewaka-publishing`  
**Branch:** `main`  
**Verification date:** 2026-09-11  
**Exact VER-01 starting baseline:** `0720af74b8aab63ca33103a67268bc7c476323de`  
**Completed DIST-01 research baseline:** `dd887add0ab08ec87539082f23c4d0f8cd1d23d2`

## Independent disposition

**Verified With Conditions**

FR-WP-03 is independently verified as sufficient foundational printing, distribution, fulfillment, returns-risk, channel-economics, and FR-WP-06 input research for PM-01 acceptance review, subject to the conditions in this report. The open conditions are not treated as completed evidence and do not authorize procurement, pricing, distribution enrollment, return-policy selection, ISBN action, direct-commerce launch, or any other Human Owner-gated execution.

No DIST-01 research file was modified to obtain this disposition.

## 1. Pre-verification governance and lineage checks

Before substantive verification, VER-01 independently confirmed:

- repository identity is exactly `efong505/ekewaka-publishing`;
- branch is exactly `main`;
- `main` HEAD at verification start was exactly `0720af74b8aab63ca33103a67268bc7c476323de`;
- that launcher commit directly descended from completed DIST-01 baseline `dd887add0ab08ec87539082f23c4d0f8cd1d23d2`;
- every governing baseline required by the launcher remained in ancestry of the starting HEAD:
  - Phase 0 governance `54218594f2f63c7e4e7a9c6b136e9f1c1c6c5bd1`;
  - FR-WP-01 accepted VER-01 `daa746783a668fca26781b669538363227ab3c5a`;
  - FR-WP-01 PM acceptance `f6f682083933db727b82c90255f6226a2afc4caa`;
  - FR-WP-02 FIN-01 completion `3470cf382b14502a27a9da5d809023909174ed8a`;
  - FR-WP-02 VER-01 `bdd86d29601f73a854557e1e08ba50c30de02f7c`;
  - FR-WP-02 PM acceptance `0e5440dcfc9e4d712019cfde1b98bc3eec8867a3`;
  - DIST-01 role definition `fe55c189f890589085298ee1cbdaa3175f6e2225`;
  - FR-WP-03 DIST-01 launcher `b00191aebdbebc4bdd4ea5f93d7f1fb95a80a848`;
  - exact DIST-01 starting baseline `2c4b67f0e4f45bd0d83a04e636c53586de32a666`;
  - completed DIST-01 research `dd887add0ab08ec87539082f23c4d0f8cd1d23d2`.

VER-01 also reviewed the current work-package register, roadmap, Human Owner gates, risk register, agent architecture, DIST-01 role definition, FR-WP-03 DIST-01 launcher, FR-WP-02 PM acceptance record, the governing master project prompt, and every artifact under `02_research/fr-wp-03/`.

## 2. Files reviewed

### Governance / role / handoff
- `00_governance/work-package-register.md`
- `00_governance/master-roadmap.md`
- `00_governance/human-owner-gates.md`
- `00_governance/risk-register.md`
- `00_governance/fr-wp-02-pm-acceptance.md`
- `01_agents/agent-architecture.md`
- `01_agents/dist-01-printing-distribution-fulfillment-agent.md`
- `18_handoffs/fr-wp-03-dist-01-printing-distribution-fulfillment-baseline-launcher.md`
- `18_handoffs/fr-wp-03-ver-01-independent-verification-launcher.md`

### Full FR-WP-03 research package
- `02_research/fr-wp-03/00-main-research-report.md`
- `02_research/fr-wp-03/01-printing-distribution-fulfillment-comparison-matrix.md`
- `02_research/fr-wp-03/02-kdp-print-baseline.md`
- `02_research/fr-wp-03/03-ingramspark-lightning-source-baseline.md`
- `02_research/fr-wp-03/04-lulu-direct-and-direct-fulfillment-baseline.md`
- `02_research/fr-wp-03/05-short-run-offset-local-printing-baseline.md`
- `02_research/fr-wp-03/06-returns-discounts-wholesale-risk-analysis.md`
- `02_research/fr-wp-03/07-volume-economics-and-channel-sensitivity-matrix.md`
- `02_research/fr-wp-03/08-fr-wp-06-financial-model-input-register.md`
- `02_research/fr-wp-03/09-unresolved-questions-gaps.md`
- `02_research/fr-wp-03/10-risk-findings.md`
- `02_research/fr-wp-03/11-recommendations-separated-from-approvals.md`
- `02_research/fr-wp-03/12-evidence-source-register.md`

## 3. Evidence independently rechecked

VER-01 independently rechecked current public/primary evidence rather than inheriting DIST-01 conclusions. Rechecks included:

### Amazon KDP
- paperback royalty mechanics and current 50%/60% tiers;
- Amazon.com $9.99 threshold for the 60% paperback tier;
- Expanded Distribution 40% royalty less printing cost;
- Expanded Distribution paperback-only / hardcover ineligibility;
- no guarantee of bookstore/library stocking or orders;
- current print-cost formula and the published 300-page U.S. B&W paperback example at $4.60;
- standard versus Expanded Distribution payment timing;
- live calculator availability.

Primary/current sources rechecked:
- https://kdp.amazon.com/en_US/help/topic/G201834330
- https://kdp.amazon.com/en_US/help/topic/G201834340
- https://kdp.amazon.com/en_US/help/topic/GQTT4W3T5AYK7L45
- https://kdp.amazon.com/en_US/help/topic/G8BKPU9AGVZSF9QF
- https://kdp.amazon.com/en_US/help/topic/GAVW3FZZAKA2KY3B

### IngramSpark / Lightning Source
- current trade-oriented 55% guidance and the need to treat discount as a sensitivity rather than a mandatory universal value;
- current user-guide caution that allowed minimum discounts can change and must be checked in live title setup;
- No / Yes-Deliver / Yes-Destroy return options;
- wholesale-cost chargeback basis;
- Yes-Deliver current published handling of $3/book to U.S. return addresses and $20/book to non-U.S./international return addresses;
- Yes-Destroy wholesale-cost chargeback without return shipping/handling;
- trade/bookstore availability positioning without placement guarantee;
- need for live title-specific publisher-compensation, print/ship, fee, and account/title setup evidence.

Primary/current sources rechecked:
- https://www.ingramspark.com/blog/how-to-sell-your-book-to-bookstores
- https://www.ingramspark.com/blog/making-your-book-returnable
- https://www.ingramspark.com/blog/why-should-i-discount-my-book
- https://www.ingramspark.com/hubfs/downloads/user-guide.pdf
- https://myaccount.ingramspark.com/Portal/Tools/PubCompCalculator
- https://myaccount.ingramspark.com/Portal/Tools/ShippingCalculator

### Lulu / Lulu Direct
- Global Distribution 50% distribution-channel share;
- gross-profit calculation after print/distribution cost and current 80% creator / 20% Lulu gross-profit split;
- Lulu Direct storefront integrations as two transactions: customer-to-merchant retail sale and merchant-to-Lulu fulfillment transaction;
- Direct Buy Button / Direct Checkout architecture in which Stripe processes payment and Lulu handles checkout-related functions including applicable tax collection, shipping calculations, and fulfillment;
- the resulting need to model tax, records, refund/chargeback, and customer responsibility by exact implementation rather than treating “Lulu Direct” as one universal merchant-of-record arrangement;
- 100–499 copy 5% bulk discount and 500+ custom-quote posture;
- Global Distribution eligibility restrictions relevant to workbook-like products.

Primary/current sources rechecked:
- https://help.lulu.com/en/support/solutions/articles/64000255464-creator-revenue-the-basics
- https://help.lulu.com/en/support/solutions/articles/64000262744-creator-revenue-guide
- https://help.lulu.com/en/support/solutions/articles/64000255458-how-do-i-set-a-retail-price-for-my-print-book
- https://help.lulu.com/en/support/solutions/articles/64000255597-publishing-a-print-book-for-global-distribution
- https://help.lulu.com/en/support/solutions/articles/64000267552
- https://help.luludirect.lulu.com/en/support/solutions/articles/64000311814-how-does-lulu-direct-merchant-pricing-work-
- https://help.luludirect.lulu.com/en/support/solutions/articles/64000311603-how-to-create-and-manage-a-lulu-direct-buy-button

### Short-run / offset / local printers
- 48 Hour Books current 10-copy minimum and current 2026 100+ / 25-additional-copy promotion and larger-volume price-break claims;
- Bookmobile current 25-copy minimum and inventory/drop-ship/API-order workflow representation;
- PrintNinja 250-copy minimum for cited hardcover/art-book products and cited production/freight timing;
- Aiken Printing public Albuquerque claims for offset, short-run digital, perfect binding, inventory/fulfillment, and mailing;
- Starline Printing public Albuquerque equipment and custom-quote representations;
- Graphic Sky public Santa Fe perfect-bound book/quote workflow and exclusion of tax/shipping from the displayed real-time quote until calculated;
- The Printer's Press Albuquerque booklet/perfect-binding and short-run public representations;
- Business Printing Services Albuquerque books/booklets and digital/offset public representations;
- Paper Tiger Santa Fe books/manuals, commercial print, and direct/bulk mail public representations;
- Ortiz Printing Santa Fe commercial/offset and hard-/soft-cover binding public representations.

These local/vendor statements remain self-published capability representations. They are adequate for identifying quote candidates but not for establishing Ekewaka-specific quality, landed economics, service levels, or vendor suitability.

## 4. Findings confirmed

VER-01 confirms the following material DIST-01 findings:

1. **KDP Amazon POD and KDP Expanded Distribution are economically distinct.** Amazon standard print royalties use 50%/60% tiers less print cost; Expanded Distribution uses 40% less print cost and is available for eligible paperbacks rather than hardcovers.
2. **The KDP illustration is arithmetically correct.** At $15.99 list and $4.60 print cost, Amazon at 60% is approximately $4.99 and Expanded Distribution at 40% is approximately $1.80 before other title/business costs.
3. **Expanded Distribution is availability, not guaranteed stocking.** The package correctly avoids treating it as a bookstore-placement commitment.
4. **Ingram trade economics require separate treatment of list price, wholesale discount, print cost, fees, and returns.** The package correctly models 55% as a trade-oriented sensitivity rather than a final Ekewaka decision.
5. **Ingram returns create contingent wholesale-value liability.** The package correctly ties return reserve exposure to the wholesale amount subject to chargeback, plus applicable Yes-Deliver handling, rather than merely manufacturing cost.
6. **Yes-Deliver and Yes-Destroy are materially different.** The package correctly preserves the physical-return versus destroy distinction and related handling treatment.
7. **Lulu Global Distribution and Lulu Direct are different architectures.** The package correctly avoids treating their economics as interchangeable.
8. **Direct commerce is not “wholesale discount avoided = margin gained.”** Payment processing, platform fees, printing, fulfillment, shipping subsidy, refunds/chargebacks, support, tax/GRT, and inventory/warehousing where applicable must be modeled.
9. **Short-run/offset quantity points are vendor/public signals, not universal break-even points.** The package correctly uses them as quote-comparison triggers.
10. **New Mexico vendors are quote candidates only.** No local vendor is represented as selected, independently qualified, or proven economically superior.
11. **The `1 / 10 / 25 / 50 / 100 / 250 / 500 / 1,000 / 5,000+` matrix is appropriate as planning sensitivity.** It explicitly rejects a universal breakpoint and requires landed-cost/risk comparison.
12. **Manufacturing, wholesale discount, retailer/distributor share, publisher proceeds, returns, shipping, fulfillment, warehousing, inventory, cash timing, setup/revision fees, and direct-commerce costs are materially distinguished.**
13. **FR-WP-06 remains separate.** The package supplies inputs and hard gates without finalizing the financial model.
14. **No universal return rate, reserve rate, final discount, or final returnability policy was selected.**
15. **All named governed risks remain active; none is closed or downgraded.**

## 5. Findings challenged, narrowed, or conditioned

No finding requires a DIST-01 research rewrite before PM review. The following interpretations are nevertheless narrowed as verification conditions:

### VC-01 — Ingram discount settings must remain live-validated
Current Ingram guidance supports 55% as a strong trade-oriented/bookstore-friendly benchmark, and current materials also describe 53%–55% as generally supporting broad retail availability. However, Ingram's current user guide states that allowed minimum discounts may change and the then-current minimum is shown in live title setup. Therefore FR-WP-06 and any later operating policy must not hard-code a historical `40%–55%` account range without a live account/title check.

### VC-02 — Public promotions and examples are benchmarks, not landed-cost evidence
48 Hour Books' current 100+ / 25-extra-copy promotion and public price-break claims are verified as current public vendor representations, but they remain promotional/benchmark inputs. They must not be normalized into Ekewaka unit economics without title-specific specifications, freight, proofs, setup/revision charges, and a current written quote/order estimate.

### VC-03 — Lulu Direct responsibility depends on the exact checkout architecture
The package correctly recognizes implementation-specific responsibility. Shopify/WooCommerce/Wix-style merchant storefront flows and Lulu Direct Buy Button/Direct Checkout flows do not allocate payment/tax/customer responsibilities identically. FR-WP-06 and later commerce architecture must identify the exact flow before assigning tax/GRT, processing, refund/chargeback, support, or merchant-of-record assumptions.

### VC-04 — Local vendor claims are candidate-screening evidence only
Aiken, Starline, Graphic Sky, Paper Tiger, Ortiz, BPS, and The Printer's Press public pages support the cited capabilities at a candidate-screening level. Those pages do not independently establish publisher-grade quality, title-specific bindery suitability, service levels, competitive landed price, inventory reporting quality, or fulfillment integration. Samples, written terms, and identical-spec quotes remain required.

## 6. Source / provenance deficiencies

The package has no material provenance defect requiring `Correction Required`, but the following limitations remain:

1. Live KDP/Ingram/Lulu calculators are linked rather than preserved as representative title-specific dated captures.
2. Ingram account-specific minimum discount, applicable current fees, printing cost, publisher compensation, and publisher-order freight have not been captured for an Ekewaka representative title.
3. Vendor promotional examples and public minimum quantities are not equivalent to written Ekewaka quotes.
4. Local-printer evidence is vendor-authored capability evidence, not independent qualification evidence.
5. No apples-to-apples quote packet yet normalizes trim, page count, paper, ink, binding, finish, proof, setup, revision, packaging, freight, receiving, storage, fulfillment, lead time, damage/reprint terms, and payment timing across candidates.
6. No evidence-backed title/category-specific return-rate sensitivity has yet been adopted for FR-WP-06.
7. No implementation-specific CPA/tax determination has yet resolved direct-commerce New Mexico GRT and related tax/accounting treatment.

These deficiencies are already substantially identified in `09-unresolved-questions-gaps.md` and appropriately remain open.

## 7. KDP verification result

**PASS — Verified With Conditions.**

The current KDP mechanics, Expanded Distribution distinctions, print-cost treatment, author-copy posture, eligibility limitations, and representative arithmetic are accurate enough for foundational planning. The condition is that title-specific live calculator/order estimates must replace the generic 300-page benchmark before FR-WP-06 hard-codes manufacturing, author-copy, or landed-cost assumptions.

The package also correctly recognizes that the KDP royalty amount is not net title profitability and excludes author royalty, overhead, marketing, taxes, title investment, and other business costs.

## 8. Ingram verification result

**PASS — Verified With Conditions.**

The package correctly captures:
- wholesale-discount sensitivity;
- 55% trade-oriented guidance;
- returnability choices;
- wholesale-value chargeback exposure;
- Yes-Deliver versus Yes-Destroy;
- current published Yes-Deliver handling;
- trade availability without guaranteed stocking/sell-through;
- need for live title/account-specific quotes and fees.

Condition: the current live account/title setup must control the actual minimum/allowed discount, fees, printing cost, compensation, and publisher-order freight used in FR-WP-06. No final returns or discount policy is verified or approved by this report.

## 9. Lulu / direct verification result

**PASS — Verified With Conditions.**

Global Distribution economics and Lulu Direct merchant/fulfillment separation are correctly distinguished. Current Lulu Direct documentation confirms the two-transaction storefront integration model and separately documents Direct Buy Button/Direct Checkout flows where Stripe/Lulu handle more of the checkout/tax/fulfillment chain.

Condition: the selected future direct-commerce architecture must be identified before merchant-of-record, payment, tax/GRT, refund/chargeback, privacy/customer-data, and support assumptions are fixed. Representative title/destination manufacturing and shipping captures remain required.

## 10. Short-run / offset / local verification result

**PASS — Verified With Conditions.**

The package correctly treats:
- 48 Hour Books 10-copy minimum and public promotion/price-break signals;
- Bookmobile 25-copy minimum and publisher-oriented fulfillment capability;
- PrintNinja's cited 250-copy product minimum as a vendor-specific offset signal;
- New Mexico printers as quote candidates rather than selected vendors.

The `250–500` offset-comparison posture is reasonable only as a procurement research trigger, not a guaranteed crossover point. The package states this correctly.

Condition: obtain identical-spec written quotes and normalize all landed-cost components before any economic ranking or procurement decision.

## 11. Returns / wholesale verification result

**PASS.**

The package correctly treats returnability as a contingent liability and correctly rejects manufacturing-cost-only reserve logic. The modeled reserve basis should start from the wholesale value subject to chargeback and then add applicable handling/shipping and timing effects.

No return-rate percentage, reserve percentage, wholesale discount, or returnability policy is approved. Evidence-backed low/base/high return sensitivities remain required for FR-WP-06.

## 12. Volume-breakpoint verification result

**PASS.**

The `1 / 10 / 25 / 50 / 100 / 250 / 500 / 1,000 / 5,000+` posture is suitable for later scenario modeling because the package explicitly labels the matrix as planning sensitivity and states that no universal quantity breakpoint is adopted.

VER-01 confirms that vendor quantity minimums and promotions should be interpreted only as signals for when to request/compare quotes. The true crossover depends on landed cost, carrying cost, sell-through, expected unsold/returned units, quality, lead time, and operational constraints.

## 13. FR-WP-06 input verification result

**PASS — Sufficient foundational input register, not ready for final model hard-coding.**

`08-fr-wp-06-financial-model-input-register.md` provides traceable classes and fields sufficient to structure later modeling of:
- Amazon POD;
- Ingram trade;
- direct POD;
- stocked direct inventory;
- event/bulk sales;
- offset/large-run printing;
- manufacturing;
- freight;
- proofs/setup/revision;
- fulfillment/pick-pack;
- warehousing/storage;
- inventory carrying/financing cost;
- payment processing/platform cost;
- return reserves;
- author copies;
- cash-conversion timing.

It also includes refund/chargeback, customer support, shrink/damage, reporting/receipt dates, return timing, and royalty accrual/payment fields. This is a strong enough handoff structure for later FIN-01 work.

The register is not sufficient to finalize FR-WP-06 because live representative costs/quotes, FR-WP-05 dependencies, evidence-backed return sensitivities, and direct-commerce implementation/tax treatment remain open.

## 14. Material risks and changes

VER-01 confirms the package appropriately carries forward:

- `RISK-003` — Unsustainable trade-title economics — remains **Critical**;
- `RISK-007` — Distributor/returns exposure — remains **High**;
- `RISK-010` — Publisher cash-flow strain — remains **High**;
- `RISK-015` — Vendor/platform dependency — remains **Medium/High**.

The additional DIST risks covering false unit-cost comparison, overstock/obsolescence, freight/damage, returns concentration, metadata/channel conflict, direct-commerce compliance, unvalidated local vendors, and premium-format margin erosion are reasonable downstream controls.

**No governed risk is closed, downgraded, or otherwise reduced by VER-01.** No risk-register modification is authorized or required by this verification.

## 15. Unresolved vendor / professional-validation items

The following remain open conditions and must not be represented as completed evidence:

1. live KDP calculator/title captures for representative paperback/hardcover configurations and author-copy landed cost to representative destinations;
2. live Ingram print-cost, publisher-compensation, current fee, discount-setting, and publisher-order shipping captures for the same specifications;
3. live Lulu Global Distribution and Lulu Direct manufacturing/shipping examples for the same specifications;
4. apples-to-apples written quotes from at least two New Mexico printers and two national short-run/offset vendors;
5. normalized freight, proof, setup, revision, packaging, pallet/carton, storage, fulfillment, lead-time, payment-timing, and damage/reprint terms;
6. possible 3PL/warehouse economics if stocked inventory is contemplated;
7. evidence-backed return-rate sensitivity assumptions by relevant title/category/channel;
8. CPA/tax review for the selected direct-commerce architecture, including New Mexico GRT and inventory/accounting/nexus implications where applicable;
9. FR-WP-05 ISBN/metadata/channel-control dependencies, including edition identity, publisher-of-record, synchronized metadata authority, and duplicate/conflicting listing controls;
10. professional/legal review where later distribution, vendor, returns, or customer terms create material obligations;
11. insurance review if meaningful publisher-owned inventory is warehoused.

## 16. Human Owner gate verification

VER-01 found no evidence in the completed DIST-01 package that DIST-01:

- selected or contracted a printer/distributor;
- created a material paid account commitment;
- placed a print order;
- set final retail pricing;
- set final wholesale discounts;
- set a final returns policy;
- purchased ISBNs;
- formed an entity;
- filed trademarks;
- acquired or published another author;
- launched Lane B or Lane C;
- conducted paid marketing;
- deployed production payment or royalty systems.

Recommendations remain explicitly separated from approvals. Edward Fong remains the Human Owner and final decision authority.

## 17. Verification conditions

FR-WP-03 is **Verified With Conditions** subject to all of the following:

1. Preserve current platform/provider terms as volatile inputs and live-recheck them before material pricing, procurement, contracting, underwriting, or launch decisions.
2. Obtain representative KDP/Ingram/Lulu title-specific landed-cost/calculator evidence before FR-WP-06 hard-codes channel economics.
3. Obtain identical-spec New Mexico and national short-run/offset quotes before ranking vendors or identifying economic breakpoints.
4. Preserve Ingram discount and returnability as sensitivities until live account/title terms and evidence-backed return-rate assumptions are available.
5. Resolve implementation-specific direct-commerce payment/tax/GRT/accounting responsibilities with appropriate professional review before launch or final financial treatment.
6. Obtain 3PL/warehouse economics before treating stocked direct inventory as an operationally modeled baseline where material.
7. Mature FR-WP-05 ISBN/metadata/channel-control dependencies before FR-WP-06 finalization.
8. Preserve all Human Owner gates and do not convert this verification into vendor, pricing, discount, returns, ISBN, entity, publication, marketing, or deployment authority.

## 18. PM-01 readiness

**Yes — FR-WP-03 is ready for PM-01 acceptance review as foundational research, with the conditions above.**

This readiness does not mean the package is procurement-ready, final-price-ready, final-returns-policy-ready, or ready for FR-WP-06 final acceptance.

## 19. Exact recommended PM next action

PM-01 should conduct a bounded FR-WP-03 acceptance review and, if PM-01 concurs, accept the package **with conditions for foundational research only** while preserving:

- all open live-quote and vendor-validation items;
- evidence-backed return-rate work;
- direct-commerce CPA/tax/GRT review;
- possible 3PL/warehouse validation;
- FR-WP-05 ISBN/metadata/channel-control dependencies;
- the requirement that FR-WP-06 not be finalized until these dependencies are sufficiently mature;
- all active governed risks and all Human Owner gates.

PM-01 should not select a vendor, set a final list price/discount/returns policy, authorize procurement, purchase ISBNs, create a material vendor commitment, or close FR-WP-03 as part of the acceptance review.

## Final verification commit note

The exact immutable final verification commit cannot be self-referentially embedded in the commit that contains this report. The exact final verification commit is the subsequent repository commit that records this independent disposition in `00_governance/work-package-register.md`; its SHA must be reported in the VER-01 execution handoff/final response after that commit is created.
