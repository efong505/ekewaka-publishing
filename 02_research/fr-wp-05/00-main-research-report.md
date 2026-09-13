# FR-WP-05 — ISBN, Metadata & Rights Foundations

**Agent:** RIGHTS-01 — ISBN, Metadata & Rights Foundations Agent  
**Research date:** 2026-09-12  
**Exact starting HEAD:** `bb4a7768ec2235b7a15df13997f9ddc381b87f8a`  
**Lifecycle at start:** AUTHORIZED  
**Target lifecycle after package completion:** REVIEW PENDING  

## Scope and governance
This package provides current foundational research only. It does not constitute legal advice, contract approval, ISBN purchase/assignment authority, final imprint approval, final publisher-of-record architecture, royalty approval, outside-author acquisition authority, or Lane B/Lane C launch authority.

The package preserves all Human Owner gates and the FR-WP-02 / FR-WP-03 PM-accepted-with-conditions boundaries. FR-WP-06 may consume traceable planning inputs from this package but must not be finalized solely by RIGHTS-01.

## Executive findings

### 1. U.S. ISBN ownership and acquisition
For U.S.-address publishers, Bowker / the U.S. ISBN Agency is the authorized source for publisher-assigned ISBNs. ISBN.org states that the U.S. agency database establishes the publisher of record associated with the assigned prefix; assigned ISBN blocks cannot properly be split, resold, or transferred to another publisher. Each format/binding generally requires a distinct ISBN, and a revised edition requires a new ISBN. An assigned ISBN is not reused.

**Operational conclusion:** if Ekewaka wants durable publisher identity and multi-channel control for Ekewaka-published editions, publisher-controlled ISBNs are structurally preferable to platform-owned free identifiers. This is a recommendation, not purchase approval.

### 2. Platform-provided identifiers are channel-constrained
KDP offers free ISBNs for paperback and hardcover, but those free ISBNs are KDP-only and display the imprint as `Independently published`. IngramSpark offers free U.S. ISBNs owned by IngramSpark, associated with `Indy Pub`, and non-transferable to other accounts/platforms. Lulu's free ISBN terms identify Lulu as publisher of record in bibliographic feeds; Lulu's bring-your-own-ISBN terms instead identify the ISBN owner/publisher and describe Lulu as a distribution agent.

**Operational conclusion:** free platform ISBNs can reduce initial cost but can compromise cross-channel consistency, publisher identity, migration flexibility, and clean publisher-of-record architecture.

### 3. ISBN ownership is not copyright ownership
An ISBN identifies a publication/product and publisher record. It does not establish copyright ownership. U.S. copyright law initially vests copyright in the author unless another rule applies (for example qualifying work-made-for-hire), and copyright ownership may be transferred in whole or in part. Exclusive licenses are treated as transfers of copyright ownership for statutory purposes; nonexclusive licenses are not.

### 4. Imprint and legal entity are related but distinct
An imprint is a publishing name associated with the publication/ISBN. It need not be identical to the legal entity name as a conceptual matter, but platform/ISBN records must be internally consistent with the publisher information registered for the ISBN. Final Ekewaka imprint/legal-entity architecture remains a Human Owner/legal-review decision and is not established here.

### 5. Publisher-of-record and service-provider roles must remain distinct
A platform can function as printer/distributor/service provider without becoming the publisher of record when the publisher supplies its own ISBN and platform terms support that structure. Conversely, accepting a platform-owned free ISBN may cause that platform or its designated imprint to appear as publisher/imprint in bibliographic data.

### 6. Metadata stewardship requires a canonical source of truth
Title, subtitle, contributors, edition, format, imprint/publisher, publication date, pricing, territorial availability, categories/subjects, descriptions, and identifier records should be governed centrally. Retailers/distributors may transform, delay, reject, or independently display downstream metadata, so stewardship does not equal complete display control.

A future Ekewaka metadata registry should therefore distinguish:
- canonical publisher metadata;
- identifier-agency metadata;
- channel-submitted metadata;
- channel-observed metadata;
- last update / effective date;
- exceptions and propagation status.

### 7. Format, edition, and revision treatment
Paperback, hardcover, and materially distinct publication formats require separate ISBN treatment. Audiobooks are ISBN-eligible; digital formats may require distinct ISBNs when separately traded/identified, although individual platforms may not require an ISBN for their ebook storefront. A new edition or material product change generally requires a new ISBN; a simple reprint or price change ordinarily does not.

Because platform rules can be stricter than the ISBN standard, channel-specific validation is required before production assignment.

### 8. Foundational rights framework
A later publishing agreement should explicitly identify, at minimum:
- copyright owner;
- rights granted and rights retained;
- exclusive/nonexclusive character;
- print, ebook, audio, translation and other subsidiary rights;
- territory;
- language;
- term;
- publication/availability obligations where adopted;
- royalty/accounting basis (without setting terms here);
- permissions/warranties responsibility;
- sublicensing/third-party exploitation boundaries;
- reversion/termination framework;
- audit/accounting access;
- post-termination inventory/data/metadata handling;
- AI-use and synthetic voice/artwork issues where applicable.

These categories are research inputs for counsel-reviewed contract frameworks, not legal conclusions or proposed final clauses.

### 9. Lane boundaries
**Lane A — trade publishing:** Ekewaka should be modeled as publisher of record for editions it publishes, using Ekewaka-controlled ISBNs where approved. Author copyright can remain with the author while Ekewaka receives specifically defined publishing rights under counsel-reviewed agreements.

**Lane B — hybrid/co-investment:** remains research-only. Any future model requires heightened disclosure of author contribution, publisher role, rights, ISBN ownership, financial participation, and reversion. No launch is authorized.

**Lane C — author services:** default boundary should keep the customer as their own publisher, with customer-controlled ISBN/publishing identity where ISBNs are used. Ekewaka should act as service provider absent an explicit separately approved publishing relationship. Service licenses should be narrow and purpose-limited.

### 10. FR-WP-06 dependencies
FR-WP-06 should model ISBN acquisition quantity/cost choices, per-format identifier counts, revision/new-edition replacement costs, metadata administration effort, platform/account dependencies, and counsel/professional-review cost categories. It must also model rights/royalty variables as configurable assumptions rather than hard-coded approved terms.

## Material risks
- `RISK-004` defective rights/royalty terms: remains Critical; requires attorney-reviewed contract framework.
- `RISK-006` ISBN ownership/provenance errors: remains High; requires central ISBN/edition ledger and no reuse.
- `RISK-013` AI/content-rights disputes: remains High; rights registry and contract framework must account for AI-assisted content, artwork, voice and training permissions.
- `RISK-015` vendor/platform dependency: remains active; platform-owned identifiers increase switching/migration friction.
- Additional FR-WP-05 risk: metadata divergence across Bowker/platform/distributor/retailer records can create discoverability, duplicate listing, publisher identity and fulfillment problems.

## Required downstream controls
1. Human Owner approval before ISBN block purchase or any production assignment.
2. Legal/publishing counsel review before final rights grants, reversion, territory, term, subsidiary-rights, audit or contract language is adopted.
3. Central identifier and rights registries before outside-author publishing operations.
4. Live platform-rule recheck before production assignment because KDP, IngramSpark and Lulu policies can change.
5. Separate Lane A/B/C account, contract, metadata and publisher-role controls.

## Disposition
Research package is complete with deliberately open professional/legal and future implementation-validation items. Independent VER-01 review is required before PM acceptance.
