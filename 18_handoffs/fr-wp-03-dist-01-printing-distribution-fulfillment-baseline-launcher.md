# FR-WP-03 — DIST-01 Printing, Distribution & Fulfillment Baseline Launcher

## Assignment
Continue as **DIST-01 — Printing, Distribution & Fulfillment Agent** for Ekewaka Publishing.

Repository: `efong505/ekewaka-publishing`  
Branch: `main`

## Governing baselines
- Required Phase 0 governance baseline: `54218594f2f63c7e4e7a9c6b136e9f1c1c6c5bd1`
- FR-WP-01 accepted verification baseline: `daa746783a668fca26781b669538363227ab3c5a`
- FR-WP-01 PM acceptance baseline: `f6f682083933db727b82c90255f6226a2afc4caa`
- FR-WP-02 FIN-01 completion baseline: `3470cf382b14502a27a9da5d809023909174ed8a`
- FR-WP-02 VER-01 verification baseline: `bdd86d29601f73a854557e1e08ba50c30de02f7c`
- FR-WP-02 PM acceptance record baseline: `0e5440dcfc9e4d712019cfde1b98bc3eec8867a3`
- DIST-01 role-definition baseline: `fe55c189f890589085298ee1cbdaa3175f6e2225`

Read the governing master project prompt and all applicable governance before substantive work.

## Authorized work package
**FR-WP-03 — Printing, Distribution & Fulfillment Baseline**

Before substantive research:
1. Verify repository identity and branch.
2. Verify current `main` HEAD and record it as the exact DIST-01 starting baseline.
3. Verify all governing baselines remain in ancestry.
4. Read current work-package register, roadmap, Human Owner gates, risk register, agent architecture, DIST-01 role definition, FR-WP-02 PM acceptance record, and the complete FR-WP-02 research package where it materially informs distribution economics.
5. Do not discard compatible later authorized work.

## Research objectives
Build a current, source-grounded baseline for Ekewaka's printing, distribution, and fulfillment choices across Lane A, Lane B research-only scenarios, Lane C service implications, and direct-to-consumer operations.

At minimum evaluate, where current evidence is available:
- KDP Print;
- IngramSpark / Lightning Source;
- Lulu / Lulu Direct;
- relevant local or regional New Mexico print options where public information is sufficient;
- short-run digital printing;
- offset printing at larger quantities;
- direct fulfillment and merchant-of-record implications;
- bookstore/library wholesale availability;
- distributor/retailer discounts;
- returnability and returns exposure;
- shipping and handling;
- warehousing/inventory exposure;
- author-copy economics;
- direct/bulk/institutional sales;
- hardcover, paperback, ebook-adjacent production considerations where they affect print/distribution architecture.

## Required analysis
Clearly distinguish:
- print/manufacturing cost;
- platform/distributor fee or margin;
- wholesale discount;
- retailer margin;
- publisher proceeds/contribution;
- returns treatment;
- shipping/fulfillment;
- inventory carrying cost;
- cash timing;
- setup/revision fees;
- volume breakpoints;
- POD vs short-run vs offset tradeoffs;
- platform-account and publisher-of-record control;
- ISBN/metadata dependencies that must be handed to FR-WP-05 rather than resolved here;
- current-price facts versus planning assumptions.

Do not infer confidential vendor economics.

## Volume matrix
Where evidence permits, compare economics/operational posture at approximately:
`1 / 10 / 25 / 50 / 100 / 250 / 500 / 1,000 / 5,000+` units.

If exact vendor quotes are unavailable, separate verified public inputs from modeled assumptions and label both clearly.

## FR-WP-06 handoff requirements
Produce traceable inputs for later financial modeling, including where applicable:
- manufacturing cost by format/quantity;
- wholesale discount options;
- returnability assumptions;
- return reserve considerations;
- fulfillment/shipping cost categories;
- author-copy cost;
- direct-sales fulfillment cost;
- setup/revision/account fees;
- inventory/warehousing cost categories;
- cash-conversion timing;
- minimum viable margin considerations;
- platform-specific sensitivity inputs.

Do not finalize FR-WP-06.

## Required governed package
Create under `02_research/fr-wp-03/` at minimum:
1. `00-main-research-report.md`
2. `01-printing-distribution-fulfillment-comparison-matrix.md`
3. `02-kdp-print-baseline.md`
4. `03-ingramspark-lightning-source-baseline.md`
5. `04-lulu-direct-and-direct-fulfillment-baseline.md`
6. `05-short-run-offset-local-printing-baseline.md`
7. `06-returns-discounts-wholesale-risk-analysis.md`
8. `07-volume-economics-and-channel-sensitivity-matrix.md`
9. `08-fr-wp-06-financial-model-input-register.md`
10. `09-unresolved-questions-gaps.md`
11. `10-risk-findings.md`
12. `11-recommendations-separated-from-approvals.md`
13. `12-evidence-source-register.md`

## Source standards
Use current authoritative or primary sources for material platform terms, fees, print-cost mechanisms, returnability, discounts, distribution reach, fulfillment mechanics, and other volatile claims. Preserve retrieval dates. Flag stale or inconsistent public pricing. Do not substitute marketing copy for a contractual or operational fact without labeling it appropriately.

## Human Owner gates
Do not:
- create paid distributor/printer accounts if doing so creates a material commitment;
- place print orders;
- accept vendor contracts;
- choose final distribution vendors;
- establish final list prices or wholesale discounts;
- establish final returns policy;
- purchase ISBNs;
- form an entity;
- file trademarks;
- publish another author's work;
- contact/acquire authors;
- launch Lane B or Lane C;
- execute paid marketing;
- deploy production payment/royalty systems.

## Completion lifecycle
When the governed research package is complete:
- update FR-WP-03 to `REVIEW PENDING`;
- do not self-verify;
- return the completed package to PM-01 for routing to VER-01.

End with exactly one disposition:

**FR-WP-03 Complete — Ready for Independent Verification**

**FR-WP-03 Complete With Open Professional/Vendor-Validation Items — Ready for Independent Verification**

or

**FR-WP-03 Incomplete — Correction / Additional Research Required**

Report exact starting baseline, exact final commit, files changed, platform/channel findings, POD/short-run/offset findings, returns/discount findings, volume economics, FR-WP-06 inputs, risks, unresolved items, Human Owner gate preservation, and exact recommended PM handoff.
