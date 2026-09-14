# FR-WP-05 — VER-01 Independent Verification Report

**Assignment:** VER-01 — Independent Review / Verification Agent  
**Repository:** `efong505/ekewaka-publishing`  
**Branch:** `main`  
**Verification date:** 2026-09-14  
**Exact verification starting baseline:** `6f48f01bb8b483b15b4cff67ad4b38519ebd2144`  
**Completed RIGHTS-01 package baseline:** `ef3a484b688a3524c4aeb8005dc682411d77857d`

## Disposition

**Verified With Conditions**

FR-WP-05 is independently verified as a sound foundational research package for ISBN, metadata, publisher-of-record, channel-control, rights, lane-boundary, and FR-WP-06 planning purposes. It is ready for PM-01 acceptance review, subject to the conditions and unresolved items below. This verification does not constitute PM acceptance and creates no Human Owner execution authority.

## Preliminary governance checks

- Repository identity and `main` branch were verified.
- The VER-01 launcher at `6f48f01bb8b483b15b4cff67ad4b38519ebd2144` descends directly from the completed FR-WP-05 RIGHTS-01 package baseline `ef3a484b688a3524c4aeb8005dc682411d77857d`.
- Phase 0 and accepted FR-WP-01/02/03 governance remain in ancestry; no incompatible later work displaced the package under review.
- The current work-package register correctly held FR-WP-05 at `REVIEW PENDING` before this verification.

## Files reviewed

All artifacts under `02_research/fr-wp-05/` were reviewed:

- `00-main-research-report.md`
- `01-isbn-ownership-acquisition-baseline.md`
- `02-publisher-of-record-imprint-architecture.md`
- `03-platform-identifier-channel-control-matrix.md`
- `04-metadata-governance-and-propagation-baseline.md`
- `05-format-edition-revision-identifier-matrix.md`
- `06-foundational-publishing-rights-framework.md`
- `07-lane-a-lane-b-lane-c-rights-boundaries.md`
- `08-fr-wp-06-financial-model-input-register.md`
- `09-unresolved-questions-gaps.md`
- `10-risk-findings.md`
- `11-recommendations-separated-from-approvals.md`
- `12-evidence-source-register.md`

The FR-WP-05 VER-01 launcher, work-package register, governing baselines, and earlier FR-WP acceptance state were also reviewed.

## Evidence independently rechecked

Material propositions were independently rechecked against current authoritative sources, including Bowker / U.S. ISBN Agency materials, KDP help, IngramSpark help/FAQ, Lulu help/terms, and U.S. Copyright Office statutory/compendium materials.

### ISBN verification result

**Verified With Condition.** Bowker remains the official U.S. ISBN agency; ISBNs identify specific publication/edition/format/publisher relationships; ISBNs are not copyright ownership; reuse is prohibited; individual ISBNs are not transferable between unrelated publishers. The package's practical control recommendation for publisher-controlled ISBNs in Lane A is supported.

**Condition / qualification:** wording that ISBN blocks or prefixes are categorically nontransferable must not be read as covering every corporate-successor situation. Bowker materials distinguish ordinary prohibited transfer of individual ISBNs to another publisher from transfer of a company's ISBN assets in certain acquisition/successor circumstances. Any future entity sale, merger, acquisition, or publisher-successor event requires a fresh agency-specific check and counsel review.

### Publisher-of-record / imprint verification result

**Verified.** The package correctly distinguishes legal entity, imprint, publisher of record, ISBN registrant/publisher identity, distributor, printer, and service provider. It does not establish a final Ekewaka imprint or publisher-of-record architecture.

### Platform identifier / channel-control verification result

**Verified.** Current primary-source checks support the package's material distinctions:
- KDP free ISBNs are KDP-only and use `Independently published`; own ISBNs permit the registered imprint and can support use outside KDP for the same edition subject to channel rules.
- IngramSpark free U.S. ISBNs are platform-owned/nontransferable, use `Indy Pub`, and are not portable to other platforms.
- Lulu free ISBN terms make Lulu.com the publisher in bibliographic feeds; Lulu bring-your-own-ISBN terms preserve the supplied publisher identity and describe Lulu as distribution agent.

Live account behavior remains an implementation-validation item.

### Metadata verification result

**Verified With Conditions.** The canonical/source-submitted-observed-exception-history model is appropriate. The package correctly separates stewardship from downstream retailer/distributor display control. Propagation latency, locked fields, correction behavior, retailer caching, and production-account behavior remain live implementation checks.

### Format / edition / revision verification result

**Verified With Conditions.** Separate print bindings/formats, revised editions, title/product changes, reprints, and price-only changes are treated consistently with ISBN guidance. KDP ebook non-requirement is correctly separated from broader ebook identifier strategy. Audiobook and digital-format architecture remains intentionally open for later channel-specific validation.

### Foundational rights verification result

**Verified With Conditions.** The package correctly separates ISBN ownership from copyright ownership; recognizes initial author ownership subject to doctrines such as work made for hire; distinguishes transfer/exclusive license from nonexclusive license; and treats contract categories as a framework rather than final legal terms. Final rights grants, exclusivity, territory, term, subsidiary rights, termination/reversion, audit, permissions, warranties, indemnity, and AI-specific clauses require qualified publishing/IP counsel.

### Lane A / Lane B / Lane C verification result

**Verified.** Lane A is treated as publisher-led trade publishing with explicit rights grants and publisher identity; Lane B remains research-only with heightened disclosure requirements; Lane C defaults to customer-as-publisher / service-provider posture. The package does not conflate the three lanes and does not authorize a Lane B or Lane C launch.

### FR-WP-06 input verification result

**Verified.** The input register supplies traceable planning categories for ISBN quantities, identifier consumption, metadata administration, revisions/relisting, publisher migration, counsel/permissions, channel/account dependencies, rights/royalty variables, audit/accounting, and reversion/wind-down costs. It does not finalize FR-WP-06 or hard-code unapproved financial terms.

## Findings challenged or qualified

1. **ISBN transfer language:** qualify broad nontransferability wording for corporate acquisition/successor scenarios; individual ISBN transfer between unrelated publishers remains prohibited.
2. **Platform policy volatility:** KDP, IngramSpark, Lulu, and Bowker operational rules must be rechecked at the time of actual implementation, account configuration, ISBN purchase, or identifier assignment.
3. **Publisher-of-record terminology:** retain the package's operational distinction, but treat final legal/account/entity consequences as counsel- and platform-specific rather than as a universal contractual rule.

No challenge requires rework of the foundational package before PM review.

## Source / provenance deficiencies

No blocking source-provenance deficiency was found. The package appropriately prefers primary/authoritative sources. Because platform and ISBN-agency web content changes over time, implementation decisions must use fresh retrievals rather than relying solely on the 2026-09-12 evidence register.

## Material risks

The package appropriately carries forward `RISK-002`, `RISK-004`, `RISK-006`, `RISK-011`, `RISK-013`, `RISK-015`, and `RISK-016`, plus FR05-R1 through FR05-R5. VER-01 closes or downgrades none of them.

## Unresolved professional / implementation items

The following remain open and are conditions of downstream use:
- publishing/IP counsel review of final rights grants and lane-specific agreements;
- live Bowker pricing and purchase/block decisions;
- production KDP/IngramSpark/Lulu account behavior and entity/imprint matching;
- metadata propagation/correction latency;
- founding-catalog ISBN provenance;
- ebook/audio identifier architecture;
- platform-account ownership/control and recovery/separation-of-duty design;
- final ISBN/metadata/rights registry data model and audit controls;
- title-specific chain-of-title and permissions before outside-author publication.

## Human Owner gate confirmation

Confirmed intact. This verification did not purchase or assign ISBNs, establish a final imprint or publisher-of-record architecture, execute contracts, acquire rights, approve royalties, form an entity, file trademarks, purchase domains, publish another author's work, launch Lane B/Lane C, deploy payment/royalty systems, conduct paid marketing, or authorize another Human Owner-gated action.

## PM readiness

**Ready for PM-01 acceptance review.** The appropriate next step is a separate PM-01 adjudication of FR-WP-05 as foundational research, with this `Verified With Conditions` disposition and all open professional/implementation conditions preserved.

## Recommended PM next action

PM-01 should independently review this verification report and the completed FR-WP-05 package, then issue an acceptance / acceptance-with-conditions / correction decision without treating VER-01 verification as PM acceptance. FR-WP-06 may not be treated as finalized merely because FR-WP-05 passed verification.

Edward Fong remains the Human Owner and final decision authority.