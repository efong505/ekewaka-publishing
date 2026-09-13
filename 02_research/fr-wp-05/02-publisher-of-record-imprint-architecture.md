# FR-WP-05 — Publisher-of-Record & Imprint Architecture

## Distinctions
**Legal entity:** the person or organization entering contracts, holding accounts, bearing tax/legal obligations and, where applicable, owning publishing assets.

**Imprint:** the publishing name associated with a publication and ISBN record. It can function as a brand distinct from the legal entity, but the exact structure must be supported by the ISBN agency, platform account records, contracts, and counsel-reviewed business architecture.

**Publisher of record:** the publisher identity associated with the ISBN/bibliographic record. It is not automatically the printer, distributor, retailer or service platform.

**Service provider/distributor:** a platform can print, distribute, fulfill, transmit metadata, or facilitate sales without owning the underlying copyright. Whether it becomes the bibliographic publisher depends materially on identifier/account terms.

## Current channel implications
- KDP: own ISBN permits the publisher/imprint registered with the ISBN agency; free KDP ISBN displays `Independently published` and is KDP-only.
- IngramSpark: own ISBN supports publisher-owned identity; its free ISBN is owned by IngramSpark and uses `Indy Pub`.
- Lulu: under Lulu's free ISBN agreement Lulu.com is publisher of record in bibliographic feeds. Under Lulu's bring-your-own-ISBN agreement, the supplied publisher is listed and Lulu states it functions as a distribution agent.
- Direct commerce: direct sales do not inherently change the ISBN publisher of record; the controlling concern is consistent product, identifier and publisher metadata across the supply chain.

## Recommended planning architecture
For Lane A, model the future target as:
`Human Owner-approved legal entity → Human Owner-approved Ekewaka imprint/publisher identity → publisher-controlled ISBNs → multiple printing/distribution/service channels`.

This preserves optionality and minimizes accidental transfer of publisher identity to a platform. It is a research recommendation only.

## Open decisions requiring Human Owner / professional review
- final legal entity name and formation;
- final imprint name(s) and trademark treatment;
- which entity/person acquires future ISBN blocks;
- account ownership and tax identity alignment;
- copyright/license-chain alignment for outside-author works;
- any alternate imprint architecture.

## Sources
KDP ISBN/imprint guidance; IngramSpark free ISBN FAQ; Lulu ISBN agreements; ISBN.org U.S. agency guidance. See `12-evidence-source-register.md`.