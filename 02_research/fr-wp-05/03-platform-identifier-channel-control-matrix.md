# FR-WP-05 — Platform Identifier & Channel-Control Matrix

| Channel / service | Publisher-controlled ISBN | Platform/free identifier | Publisher/imprint effect | Cross-channel control implication |
|---|---|---|---|---|
| KDP Print | Accepted if ISBN metadata matches; can reflect publisher's registered imprint | Free KDP ISBN for paperback/hardcover | Free ISBN displays `Independently published` | Free ISBN is KDP-only; own ISBN supports use outside KDP for the same edition subject to other channel rules |
| KDP ebook | ISBN not required by KDP | Amazon ASIN assigned | ASIN is an Amazon product identifier, not publisher ISBN ownership | Publisher may choose separate ISBN strategy outside KDP if needed |
| IngramSpark | Own ISBN supported | Free U.S. ISBN owned by IngramSpark | Free ISBN uses `Indy Pub` | Free ISBN is non-transferable/platform-bound; own ISBN provides cleaner publisher identity and portability |
| Lulu Global Distribution | Own ISBN supported; publisher data must match agency record | Free Lulu ISBN available | Free ISBN agreement makes Lulu.com publisher in bibliographic feeds; BYO agreement lists supplied publisher | BYO ISBN better preserves publisher-of-record identity; Lulu may remain bibliographic feed source while distribution is active |
| Direct sales / own store | Existing valid ISBN may be used for identified edition where applicable | Internal SKU may supplement but does not replace industry ISBN when trade identification is needed | Publisher remains governed by ISBN registration | Strongest direct control over storefront data but downstream payment/fulfillment services may have their own product IDs |
| Bookstores/libraries/wholesale | Industry ISBN expected for trade identification | Platform-specific IDs generally not substitutes across the industry | Bibliographic records typically surface ISBN-linked publisher/imprint | Clean publisher-controlled ISBN/metadata improves consistency and discoverability |

## Account-control principles
1. The account that owns/controls channel metadata should be documented independently from copyright ownership.
2. Password/account ownership is not publisher-of-record status.
3. Platform bibliographic feeds can overwrite or lag canonical publisher metadata.
4. Ekewaka should retain an internal canonical record plus observed channel-state records.
5. Free identifiers should never be assumed portable without explicit current platform authority.

## Governance conclusion
No channel account was created or altered and no identifier was assigned. Final channel architecture remains Human Owner-gated.