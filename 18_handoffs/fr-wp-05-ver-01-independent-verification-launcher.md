# FR-WP-05 — VER-01 Independent Verification Launcher

## Assignment
Continue as **VER-01 — Independent Review / Verification Agent** for Ekewaka Publishing.

Repository: `efong505/ekewaka-publishing`  
Branch: `main`

## Governing baselines
- Required Phase 0 governance baseline: `54218594f2f63c7e4e7a9c6b136e9f1c1c6c5bd1`
- FR-WP-01 accepted VER-01 baseline: `daa746783a668fca26781b669538363227ab3c5a`
- FR-WP-01 PM acceptance baseline: `f6f682083933db727b82c90255f6226a2afc4caa`
- FR-WP-02 PM acceptance baseline: `0e5440dcfc9e4d712019cfde1b98bc3eec8867a3`
- FR-WP-03 DIST-01 completion baseline: `dd887add0ab08ec87539082f23c4d0f8cd1d23d2`
- FR-WP-03 VER-01 verification baseline: `aa8e86f535f5191d4f9d8513cd4002c712243236`
- FR-WP-03 PM acceptance baseline: `4d03266a12be5600a1abec86812928ba4b674074`
- RIGHTS-01 role-definition baseline: `652d596a2d5c600f460e088121fda023611c5845`
- FR-WP-05 RIGHTS-01 launcher baseline: `92adb76177fc4a3e047c81d805cee4928f95ba7f`
- FR-WP-05 RIGHTS-01 starting baseline: `bb4a7768ec2235b7a15df13997f9ddc381b87f8a`
- Completed FR-WP-05 RIGHTS-01 baseline: `ef3a484b688a3524c4aeb8005dc682411d77857d`

Read the governing master project prompt and all applicable governance before substantive work.

## Completed package under review
**FR-WP-05 — ISBN, Metadata & Rights Foundations**

RIGHTS-01 disposition:

**FR-WP-05 Complete With Open Professional/Implementation-Validation Items — Ready for Independent Verification**

## Verification boundary
This is an independent verification assignment. Do not inherit RIGHTS-01 conclusions without checking source fidelity and current evidence. Do not rewrite RIGHTS-01 research merely to make it pass. Preserve separation among RIGHTS-01 research, VER-01 verification, PM-01 acceptance, and Human Owner authority.

## Required preliminary checks
Before substantive verification:
1. Verify repository identity is exactly `efong505/ekewaka-publishing` and branch is exactly `main`.
2. Record the exact current `main` HEAD as the VER-01 starting baseline.
3. Verify all governing baselines above remain in ancestry.
4. Verify FR-WP-05 completed baseline `ef3a484b688a3524c4aeb8005dc682411d77857d` remains in ancestry.
5. Read the current work-package register, roadmap, Human Owner gates, risk register, agent architecture, RIGHTS-01 role definition, FR-WP-05 RIGHTS-01 launcher, FR-WP-01/02/03 acceptance records, and every artifact under `02_research/fr-wp-05/`.
6. Do not discard compatible later authorized work.

## Independent verification scope
Independently verify at minimum:

### ISBN / publisher identity
- Bowker / U.S. ISBN Agency role and current authoritative-source support.
- Publisher-owned ISBN versus platform-provided identifier distinctions.
- Transferability/nontransferability rules and publisher-prefix implications.
- Format, edition, revision, publisher-change, and identifier-reuse claims.
- Whether recommendations improperly imply approval to purchase or assign ISBNs.

### Publisher-of-record / imprint architecture
- Distinction among legal entity, imprint, publisher of record, ISBN registrant, and distribution/service provider.
- KDP own-ISBN versus free-ISBN implications.
- IngramSpark free-ISBN implications.
- Lulu free-ISBN versus bring-your-own-ISBN publisher-of-record implications.
- Whether any final Ekewaka imprint or publisher-of-record architecture was improperly established.

### Platform identifier / channel control
- Portability and cross-channel implications of publisher-owned versus platform-provided ISBNs.
- Account-control and channel-control assertions where evidence supports them.
- Any platform-specific limitations that require live account or implementation validation.

### Metadata governance
- Canonical metadata concept and separation among source-of-truth, submitted, observed, exception, and history states.
- KDP, Ingram, Lulu metadata consistency/locking/propagation claims.
- Whether metadata stewardship is correctly distinguished from downstream retailer/distributor display behavior.

### Format / edition / revision treatment
- Paperback/hardcover separate ISBN treatment.
- Digital/audio identifier treatment and any conditional language.
- Material revision/new edition versus reprint/price-change treatment.
- Publisher-change implications.
- Founding-catalog migration dependency for existing Edward Fong titles.

### Foundational rights framework
- ISBN ownership versus copyright ownership distinction.
- Initial copyright ownership under U.S. law.
- Transfer of copyright ownership, exclusive-license, and nonexclusive-license distinctions.
- Whether the package appropriately treats print, ebook, audio, translation, language, territory, term, exclusivity, sublicensing, subsidiary rights, reversion/termination, permissions, audit/accounting, warranties, and AI-related rights as framework categories rather than final contract language.
- Flag any legal proposition that requires qualified counsel rather than being safely treated as operational/foundational research.

### Lane boundaries
Independently verify Lane A / Lane B / Lane C treatment:
- Lane A publisher-of-record posture for editions actually published by Ekewaka while author copyright may be retained and specifically licensed.
- Lane B research-only status and heightened disclosure requirements.
- Lane C customer-as-publisher default and narrowly scoped service-license posture.
- Ensure trade publishing, hybrid/co-investment research, and author services are not conflated.

### FR-WP-06 inputs
Review `02_research/fr-wp-05/08-fr-wp-06-financial-model-input-register.md` and verify that it supplies traceable planning inputs for ISBN quantities/blocks, identifier consumption, metadata administration, revision/relisting, migration, counsel/permissions, channel/account dependencies, rights/royalty variables, audit/accounting infrastructure, and reversion/wind-down costs without finalizing FR-WP-06.

### Risks
Independently assess whether relevant governed risks are appropriately carried forward, including where applicable `RISK-002`, `RISK-004`, `RISK-006`, `RISK-011`, `RISK-013`, `RISK-015`, and `RISK-016`, plus metadata divergence, identifier underplanning, accidental publisher-role transfer, ambiguous rights scope, and post-reversion/channel wind-down risks.

Do not close or downgrade risks without governed evidence.

### Open professional / implementation items
Confirm that the package preserves rather than silently resolves:
- publishing/IP counsel review of final rights grants, exclusivity, territory, term, subsidiary rights, reversion/termination, audit, permissions, warranties, AI language, and lane-specific agreements;
- live Bowker pricing;
- actual KDP/Ingram/Lulu account behavior;
- metadata propagation/correction latency;
- founding-catalog ISBN provenance;
- ebook/audio identifier architecture;
- account ownership;
- eventual ISBN/metadata/rights registry data model.

### Human Owner gates
Confirm RIGHTS-01 did not:
- purchase or assign ISBNs;
- establish final imprint or publisher-of-record architecture;
- execute contracts or acquire rights;
- approve royalties;
- form an entity;
- file trademarks;
- purchase domains;
- publish another author's work;
- launch Lane B or Lane C;
- deploy payment/royalty systems;
- conduct paid marketing;
- execute any other Human Owner-gated action.

## Verification artifact
Create:
`15_verification/fr-wp-05/00-ver-01-independent-verification-report.md`

Update `00_governance/work-package-register.md` only to record the independent verification disposition.

Do not mark FR-WP-05 `PM ACCEPTED` or `CLOSED`.

## Required disposition
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
8. ISBN verification result;
9. publisher-of-record/imprint verification result;
10. platform identifier/channel-control verification result;
11. metadata verification result;
12. format/edition/revision verification result;
13. foundational rights verification result;
14. Lane A/B/C verification result;
15. FR-WP-06 input verification result;
16. material risks and any changes;
17. unresolved professional/implementation items;
18. confirmation that Human Owner gates remained intact;
19. whether FR-WP-05 is ready for PM-01 acceptance;
20. exact recommended PM next action.

Edward Fong remains the Human Owner and final decision authority.