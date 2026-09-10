# FR-WP-03 — KDP Print Baseline

**Retrieval date:** 2026-09-10  
**Evidence class:** Current Amazon KDP primary sources unless labeled modeled.

## Current verified mechanics
- Paperback royalties on Amazon marketplaces use either **50% or 60% of tax-exclusive list price less printing cost**, depending on list price and marketplace.
- On Amazon.com, paperback list prices **$9.99 and above** currently qualify for the 60% tier; $9.98 and below use 50%.
- KDP's current U.S. example for a **300-page black-ink paperback** uses a **$4.60** printing cost, calculated as `$1.00 + (300 × $0.012)` for the cited configuration.
- KDP prints retail copies on demand, so the publisher does not need to pre-purchase retail inventory.
- Expanded Distribution pays **40% of list price less printing cost**.
- Expanded Distribution is for eligible paperbacks; **hardcovers are not eligible**.
- Expanded Distribution makes eligible books available to distributors used by bookstores, online retailers, libraries and academic institutions, but KDP explicitly states this does **not guarantee** distributor acceptance, bookstore/library listing, stocking, or orders.
- Standard print royalties are generally paid about **60 days after month-end**. KDP's pricing guidance states Expanded Distribution payments are approximately **90 days after month-end**; the Expanded Distribution help page describes payment about 60 days after the distributor reports the sale, creating effectively longer cash timing.

## Printing cost structure
KDP states print cost varies by marketplace, page count, ink type and trim category. The published formula is:

`fixed cost + (page count × per-page cost) = printing cost`

Current U.S. black-ink regular-trim tables include a fixed-only treatment for low page counts and page-based pricing above the threshold. Because exact title configuration controls cost, FR-WP-06 should ingest a live KDP calculator output for every modeled format rather than reuse one generic cost.

## Modeled illustration — not an Ekewaka price decision
Representative assumptions only:
- U.S. paperback
- 300 pages
- black ink
- regular trim
- KDP published example print cost: $4.60
- modeled list price: $15.99

Results:
- Amazon.com: `(60% × $15.99) - $4.60 = $4.99` approximate publisher royalty.
- Expanded Distribution: `(40% × $15.99) - $4.60 = $1.80` approximate publisher royalty.

These amounts are **publisher receipts before** author royalty, editorial/design investment, overhead, marketing, tax effects and other title-level costs.

## Author-copy and bulk implications
KDP author copies are a useful comparison point for events, author allocations and direct/bulk sales because copies can be procured at print cost plus applicable shipping/taxes. Exact landed cost is title-, quantity- and destination-specific and must be captured by live order estimate before FR-WP-06 uses it as a hard input.

KDP does not create a short-run manufacturing discount curve comparable to conventional printers; retail POD economics remain fundamentally per-copy. Therefore, at 50/100/250/500+ known-unit demand, DIST-01 recommends comparing KDP landed author-copy cost against short-run quotes.

## Bookstore/library posture
KDP Expanded Distribution is useful as a broad-availability option but is not equivalent to a deliberate trade-sales architecture. Its 40% publisher royalty formula leaves materially less publisher contribution than Amazon standard distribution for the same list/print cost, and KDP does not expose publisher-selected trade discount/returns terms.

## Risks / dependencies
- Margin compression on low list prices or high page counts.
- Expanded Distribution economics may be insufficient for some title cost structures.
- Metadata/ISBN ownership and edition control must be resolved in FR-WP-05.
- KDP-only dependence would increase platform concentration risk.
- Amazon-native print and Ingram trade distribution for the same publisher edition require metadata/ISBN/channel configuration review to avoid duplicate or conflicting listings.

## Primary sources
- https://kdp.amazon.com/en_US/help/topic/G201834330
- https://kdp.amazon.com/en_US/help/topic/G201834340
- https://kdp.amazon.com/en_US/help/topic/G8BKPU9AGVZSF9QF
- https://kdp.amazon.com/en_US/help/topic/GQTT4W3T5AYK7L45
- https://kdp.amazon.com/en_US/help/topic/GAVW3FZZAKA2KY3B
- https://kdp.amazon.com/en_US/royalty-calculator
