# FR-WP-03 — VER-01 Independent Verification Launcher

## Assignment
Continue as **VER-01 — Independent Review / Verification Agent** for Ekewaka Publishing.

Repository: `efong505/ekewaka-publishing`  
Branch: `main`

## Governing baselines
- Required Phase 0 governance baseline: `54218594f2f63c7e4e7a9c6b136e9f1c1c6c5bd1`
- FR-WP-01 accepted verification baseline: `daa746783a668fca26781b669538363227ab3c5a`
- FR-WP-01 PM acceptance baseline: `f6f682083933db727b82c90255f6226a2afc4caa`
- FR-WP-02 FIN-01 completion baseline: `3470cf382b14502a27a9da5d809023909174ed8a`
- FR-WP-02 VER-01 verification baseline: `bdd86d29601f73a854557e1e08ba50c30de02f7c`
- FR-WP-02 PM acceptance baseline: `0e5440dcfc9e4d712019cfde1b98bc3eec8867a3`
- DIST-01 role-definition baseline: `fe55c189f890589085298ee1cbdaa3175f6e2225`
- FR-WP-03 DIST-01 launcher baseline: `b00191aebdbebc4bdd4ea5f93d7f1fb95a80a848`
- FR-WP-03 exact DIST-01 starting baseline: `2c4b67f0e4f45bd0d83a04e636c53586de32a666`
- Completed FR-WP-03 DIST-01 research baseline: `dd887add0ab08ec87539082f23c4d0f8cd1d23d2`

Read the governing master project prompt and all applicable governance before substantive work.

## Authorized verification target
**FR-WP-03 — Printing, Distribution & Fulfillment Baseline**

DIST-01 disposition:

**FR-WP-03 Complete With Open Professional/Vendor-Validation Items — Ready for Independent Verification**

VER-01 must independently assess the completed package and must not inherit DIST-01 conclusions without checking the supporting evidence.

## Before substantive verification
1. Verify repository identity is exactly `efong505/ekewaka-publishing`.
2. Verify branch is exactly `main`.
3. Verify current `main` HEAD and record it as the exact VER-01 starting baseline.
4. Verify all governing baselines remain in ancestry.
5. Verify completed FR-WP-03 baseline `dd887add0ab08ec87539082f23c4d0f8cd1d23d2` remains in ancestry.
6. Read current work-package register, roadmap, Human Owner gates, risk register, agent architecture, DIST-01 role definition, FR-WP-03 DIST-01 launcher, FR-WP-02 PM acceptance record, and the full completed FR-WP-03 package.
7. Do not discard compatible later authorized work.

## Required files to review
Review every artifact under `02_research/fr-wp-03/`, including:
- `00-main-research-report.md`
- `01-printing-distribution-fulfillment-comparison-matrix.md`
- `02-kdp-print-baseline.md`
- `03-ingramspark-lightning-source-baseline.md`
- `04-lulu-direct-and-direct-fulfillment-baseline.md`
- `05-short-run-offset-local-printing-baseline.md`
- `06-returns-discounts-wholesale-risk-analysis.md`
- `07-volume-economics-and-channel-sensitivity-matrix.md`
- `08-fr-wp-06-financial-model-input-register.md`
- `09-unresolved-questions-gaps.md`
- `10-risk-findings.md`
- `11-recommendations-separated-from-approvals.md`
- `12-evidence-source-register.md`

## Independent verification scope

### 1. Source freshness and authority
Independently re-check current authoritative or primary-source claims where practicable for:
- KDP Print royalty and print-cost mechanics;
- KDP Expanded Distribution eligibility and economics;
- IngramSpark/Lightning Source wholesale discount, returnability, return charges, and fee mechanics;
- Lulu Global Distribution and Lulu Direct economics;
- short-run and offset vendor quantity signals;
- any public New Mexico printer capability claims materially relied upon.

Identify stale, conflicting, ambiguous, marketing-only, or non-authoritative evidence.

### 2. Arithmetic and economic treatment
Independently verify representative calculations, especially:
- KDP example arithmetic;
- Expanded Distribution arithmetic;
- Ingram compensation/returns logic;
- Lulu distribution/direct-sales treatment;
- wholesale discount versus manufacturing cost distinctions;
- returns chargeback basis;
- direct-commerce contribution treatment.

Do not approve final pricing, discount, returns, or royalty decisions.

### 3. KDP verification
Verify whether the package accurately distinguishes:
- Amazon retail POD;
- Expanded Distribution;
- author copies;
- print cost;
- royalty percentage mechanics;
- paperback/hardcover eligibility limitations;
- bookstore/library stocking limitations.

### 4. Ingram verification
Verify:
- wholesale discount treatment;
- 55% trade-oriented discount framing;
- returnability choices;
- wholesale-value chargeback exposure;
- Yes-Deliver and Yes-Destroy distinctions;
- return shipping/handling treatment;
- bookstore/library/trade-wholesale positioning;
- need for live title-specific quotes and fees.

### 5. Lulu/direct verification
Verify separation between:
- Lulu Global Distribution;
- Lulu Direct merchant/direct-commerce architecture;
- manufacturing/fulfillment transaction;
- customer retail transaction;
- bulk discount/public quantity claims;
- payment processing, shipping, refunds/chargebacks, support, and tax/GRT responsibilities.

### 6. Short-run / offset / local vendor verification
Verify that:
- quantity thresholds are represented as public vendor signals rather than universal economic truths;
- local New Mexico vendors are correctly described as quote candidates, not selected or fully validated book manufacturers;
- no confidential vendor economics are inferred;
- public capabilities, minimums, and price-break claims are source-supported;
- landed-cost validation remains open where it should.

### 7. Volume-breakpoint reasoning
Review the approximate `1 / 10 / 25 / 50 / 100 / 250 / 500 / 1,000 / 5,000+` posture.

Determine whether the package appropriately treats these as planning/quote-comparison thresholds rather than universal break-even points.

### 8. Returns / wholesale risk
Independently verify whether the package correctly models returns as a contingent liability and whether reserve exposure should be tied to the wholesale amount subject to chargeback rather than merely manufacturing cost.

Confirm no final return rate, reserve rate, wholesale discount, or returnability policy was selected.

### 9. FR-WP-06 input completeness
Review `08-fr-wp-06-financial-model-input-register.md` and determine whether it supplies traceable inputs for later modeling of:
- Amazon POD;
- Ingram trade;
- direct POD;
- stocked direct inventory;
- events/bulk;
- offset/large-run scenarios;
- manufacturing;
- freight;
- proofs/setup;
- fulfillment;
- warehousing;
- inventory carrying cost;
- payment processing;
- returns reserves;
- author copies;
- cash-conversion timing.

Do not finalize FR-WP-06. FR-WP-05 remains a dependency.

### 10. Open vendor/professional validation
Confirm that open items remain clearly labeled, including:
- live representative KDP/Ingram/Lulu landed-cost captures;
- apples-to-apples New Mexico and national printer quotes;
- freight/proof/setup/storage/fulfillment terms;
- possible 3PL economics;
- evidence-backed return-rate sensitivities;
- CPA/tax review for direct commerce and New Mexico GRT;
- FR-WP-05 ISBN/metadata/channel-control dependencies.

Do not treat those unresolved items as completed evidence.

### 11. Risk verification
Independently assess whether the package appropriately carries forward or reinforces:
- `RISK-003` — unsustainable trade-title economics;
- `RISK-007` — distributor/returns exposure;
- `RISK-010` — publisher cash-flow strain;
- `RISK-015` — vendor/platform dependency;
- additional inventory, freight, quote-comparability, metadata/channel, and direct-commerce risks.

Do not close or downgrade risks without explicit governed basis.

### 12. Human Owner gates
Confirm DIST-01 did not improperly:
- select or contract a printer/distributor;
- create a material paid account commitment;
- place a print order;
- set final retail pricing;
- set final wholesale discounts;
- set a final returns policy;
- purchase ISBNs;
- form an entity;
- file trademarks;
- acquire or publish another author;
- launch Lane B or Lane C;
- conduct paid marketing;
- deploy production payment or royalty systems.

Recommendations and verified research remain distinct from Human Owner approval.

## Verification artifact
Create:

`15_verification/fr-wp-03/00-ver-01-independent-verification-report.md`

Do not modify DIST-01 research merely to make it pass.

Update `00_governance/work-package-register.md` only to record the independent verification disposition.

Do not mark FR-WP-03 `PM ACCEPTED` or `CLOSED`.

## Required independent disposition
Issue exactly one:

**Verified**

**Verified With Conditions**

**Correction Required**

or

**Not Ready**

Then report:
1. exact verification starting baseline;
2. exact final verification commit;
3. files reviewed;
4. evidence independently rechecked;
5. findings confirmed;
6. findings corrected or challenged;
7. source/provenance deficiencies;
8. KDP verification result;
9. Ingram verification result;
10. Lulu/direct verification result;
11. short-run/offset/local verification result;
12. returns/wholesale verification result;
13. volume-breakpoint verification result;
14. FR-WP-06 input verification result;
15. material risks and any changes;
16. unresolved vendor/professional-validation items;
17. confirmation that all Human Owner gates remained intact;
18. whether FR-WP-03 is ready for PM-01 acceptance;
19. exact recommended PM next action.

Edward Fong remains the Human Owner and final decision authority.
