# Ekewaka Publishing — Work Package Register

## Lifecycle
`PLANNED → AUTHORIZED → IN PROGRESS → REVIEW PENDING → VERIFIED → PM ACCEPTED → CLOSED`

Exception states: `BLOCKED`, `CORRECTION REQUIRED`, `SUPERSEDED`, `CANCELLED`.

## Phase 1 — Foundational Research

| ID | Work package | Owner | Status | Key dependencies |
|---|---|---|---|---|
| FR-WP-01 | Legal, Entity, Name & Brand Clearance Foundations | LEGAL-01 / EVID-01 / VER-01 | PM ACCEPTED — WITH CONDITIONS | VER-01 independently re-verified the supplemented package and issued **Verified With Conditions** at `daa746783a668fca26781b669538363227ab3c5a`. PM-01 accepted the package for foundational-research purposes only. CR-01/CR-02 are resolved for the required captured authoritative query sets; CR-03 remains resolved for foundational scope. Legal name/trademark clearance is not established; all professional-review and Human Owner execution gates remain open. See `00_governance/fr-wp-01-pm-acceptance.md`. |
| FR-WP-02 | Publishing Business Model & Industry Benchmark | FIN-01 / VER-01 | PM ACCEPTED — WITH CONDITIONS | VER-01 independently verified the completed FIN-01 package and issued **Verified With Conditions** at `bdd86d29601f73a854557e1e08ba50c30de02f7c`. PM-01 accepted the package for foundational business-model research only at `0e5440dcfc9e4d712019cfde1b98bc3eec8867a3`. Volatile platform/provider economics must be rechecked before material downstream decisions; Lane B remains research-only; Human Owner gates remain intact. See `00_governance/fr-wp-02-pm-acceptance.md`. |
| FR-WP-03 | Printing, Distribution & Fulfillment Baseline | DIST-01 / VER-01 | PM ACCEPTED — WITH CONDITIONS | VER-01 independently verified the completed DIST-01 package and issued **Verified With Conditions** at `aa8e86f535f5191d4f9d8513cd4002c712243236`. PM-01 accepted the package for foundational printing/distribution/fulfillment research only at `4d03266a12be5600a1abec86812928ba4b674074`. Live landed-cost captures, identical-spec vendor quotes, return-rate sensitivities, CPA/GRT review, and 3PL economics remain open. No vendor/procurement authority is created. See `00_governance/fr-wp-03-pm-acceptance.md`. |
| FR-WP-04 | Author Services Competitive Benchmark | SERV-01 | PLANNED | Phase 0 complete; separately releasable; not a dependency for bounded FR-WP-06 execution |
| FR-WP-05 | ISBN, Metadata & Rights Foundations | RIGHTS-01 / VER-01 | PM ACCEPTED — WITH CONDITIONS | VER-01 independently verified the completed RIGHTS-01 package and issued **Verified With Conditions** at `906f39ac14a3e760b7b40d2f2119d9a794fd241b`. PM-01 accepted the package for foundational ISBN/metadata/rights research only at `1bebcb52f66917be02abd95271be58dd0f16c384`. Counsel review, live platform/Bowker rechecks, founding-catalog provenance work, identifier/account/data-model implementation validation, corporate-successor qualification, and all Human Owner execution gates remain open. See `00_governance/fr-wp-05-pm-acceptance.md`. |
| FR-WP-06 | Foundational Financial Model | FIN-01 | AUTHORIZED | FR-WP-02, FR-WP-03, and FR-WP-05 are PM accepted with conditions; bounded launcher `18_handoffs/fr-wp-06-fin-01-foundational-financial-model-launcher.md` governs execution. Open upstream vendor/legal/tax/implementation conditions must remain explicit assumptions or unresolved inputs. |

## Immediate sequencing
1. FR-WP-01 is **PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL RESEARCH ONLY)**; `RISK-001` remains High and no legal-clearance or execution authority is created.
2. FR-WP-02 is **PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL BUSINESS-MODEL RESEARCH ONLY)**; Lane B remains research-only and volatile economics require live rechecks before material decisions.
3. FR-WP-03 is **PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL PRINTING / DISTRIBUTION / FULFILLMENT RESEARCH ONLY)**; vendor/procurement and Human Owner gates remain intact.
4. FR-WP-05 is **PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL ISBN / METADATA / RIGHTS RESEARCH ONLY)**; counsel, live platform/Bowker, provenance, account-control, registry, and chain-of-title conditions remain open.
5. The roadmap identifies FR-WP-02, FR-WP-03, and FR-WP-05 as the material feeder packages for FR-WP-06. Those dependencies are now sufficiently mature for a bounded FR-WP-06 release.
6. PM-01 established `18_handoffs/fr-wp-06-fin-01-foundational-financial-model-launcher.md`; FR-WP-06 is now **AUTHORIZED** for foundational financial modeling only.
7. FR-WP-04 remains **PLANNED** and separately releasable. FR-WP-06 must explicitly identify where future FR-WP-04 work is still required before any Lane C public package/pricing decision.
8. FR-WP-06 must not self-verify. Upon completion it must move only to `REVIEW PENDING` and return to PM-01 for independent VER-01 review.
9. No price, royalty, acquisition, procurement, ISBN, rights, entity, tax, Lane B/Lane C, outside-author, marketing, payment/royalty, or other Human Owner-gated execution authority is created by this release.

## FR-WP-01 final PM disposition

**PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL RESEARCH ONLY)**

This does not constitute legal name availability, trademark clearance, registrability, likelihood-of-confusion clearance, final legal approval, entity-formation approval, tax-election approval, contract approval, or authorization for any filing, purchase, launch, outreach, or other Human Owner-gated action.

## FR-WP-02 final PM disposition

**PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL BUSINESS-MODEL RESEARCH ONLY)**

This acceptance preserves live-recheck requirements for volatile platform/provider economics, Lane B research-only status, downstream dependencies, attorney/CPA/market-validation conditions, and all Human Owner gates. No pricing, royalty, acquisition, contract, vendor, launch, ISBN, payment-system, publication, marketing, entity, or trademark authority is created.

## FR-WP-03 final PM disposition

**PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL PRINTING / DISTRIBUTION / FULFILLMENT RESEARCH ONLY)**

This acceptance preserves live platform/vendor landed-cost rechecks, apples-to-apples printer quotes, return-rate sensitivity validation, CPA/tax/GRT review, possible 3PL validation, active risks, and all Human Owner gates. It does not select or authorize a printer, distributor, fulfillment provider, quote, order, price, wholesale discount, returns policy, inventory commitment, ISBN action, outside-author publication, Lane B/Lane C launch, paid marketing, or payment/royalty deployment.

## FR-WP-05 final PM disposition

**PM ACCEPTED — WITH CONDITIONS (FOUNDATIONAL ISBN / METADATA / RIGHTS RESEARCH ONLY)**

PM-01 accepts the independently verified FR-WP-05 package for foundational planning, downstream architecture, governed ISBN/metadata/rights control design, and FR-WP-06 input development only.

The acceptance preserves all VER-01 conditions: counsel review of final rights and lane agreements; live Bowker and platform-policy rechecks; the corporate-successor/acquisition qualification to broad ISBN nontransferability language; founding-catalog ISBN provenance; ebook/audio identifier architecture; platform account ownership/control; registry/audit-control implementation; title-specific chain-of-title and permissions review; and all active project risks.

This acceptance does not purchase or assign ISBNs, establish a final imprint/publisher-of-record/entity/account architecture, execute contracts or acquire rights, approve royalties or other financial terms, publish another author's work, launch Lane B/Lane C, deploy payment/royalty systems, file trademarks, purchase domains, conduct paid marketing, or execute any Human Owner-gated action. See `00_governance/fr-wp-05-pm-acceptance.md`.

## FR-WP-06 current PM disposition

**AUTHORIZED — FIN-01 Foundational Financial Model may proceed.**

This authorization is limited to auditable modeling, scenario analysis, assumption governance, and recommendations separated from approvals. FIN-01 must preserve unresolved upstream conditions as explicit assumptions or unresolved inputs, must not treat FR-WP-04 as completed, must not approve final prices/royalties/acquisition economics/service prices/reserves or other financial decisions, and must return the completed package for independent VER-01 review before any PM acceptance.
