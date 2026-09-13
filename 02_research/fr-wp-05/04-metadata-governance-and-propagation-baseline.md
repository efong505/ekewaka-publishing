# FR-WP-05 — Metadata Governance & Propagation Baseline

## Canonical publisher metadata
Ekewaka should maintain one authoritative title record containing at minimum:
- title / subtitle;
- contributors and roles;
- edition statement;
- format/binding;
- ISBN and other channel identifiers;
- publisher/imprint;
- publication/on-sale dates;
- language;
- description;
- subject/category codes and keywords;
- dimensions/page count where applicable;
- list prices/currencies;
- territorial availability;
- rights availability flags;
- series data;
- cover/interior version references;
- lifecycle status and timestamps.

## Stewardship vs display control
**Metadata stewardship** means maintaining accurate canonical data and submitting authorized updates. It does not guarantee how or when a retailer/distributor displays, normalizes, merges or caches that data.

KDP requires consistency between ISBN agency records and submitted own-ISBN publisher data and expects visible title/author information to match metadata. IngramSpark distributes title metadata to resellers. Lulu identifies several fields as locked for globally distributed ISBN-bearing projects and warns that metadata changes may require project recreation/new ISBN treatment depending on the change.

## Proposed control model
1. Canonical publisher record.
2. Identifier-agency record.
3. Per-channel submission record.
4. Per-channel observed/display record.
5. Exception queue for mismatches.
6. Change log with effective date, actor and reason.
7. Controlled approval for identifier-sensitive changes.

## Propagation risks
- retailer cache/update lag;
- duplicate listings;
- inconsistent imprint names;
- title/author punctuation/capitalization drift;
- category remapping by retailer;
- price/availability latency;
- metadata lock after distribution;
- platform policy changes.

## Downstream systems dependency
SYS-01 should eventually model metadata versioning and channel-state reconciliation rather than a single mutable row. RIGHTS-01 recommends immutable identifier history and explicit edition/format relationships.

## Boundary
No live retailer metadata was changed by this research.