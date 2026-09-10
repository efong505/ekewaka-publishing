# FR-WP-03 — Lulu Direct and Direct Fulfillment Baseline

**Retrieval date:** 2026-09-10  
**Evidence class:** Current Lulu primary sources unless labeled model assumption.

## 1. Separate Lulu architectures
Lulu should not be treated as one economic channel.

### Lulu Global Distribution
Current Lulu guidance states:
- print retail distribution sends **50% of retail price** to distribution channels;
- remaining gross profit is calculated after print cost;
- Lulu receives **20% of gross profit** and the creator receives **80%**;
- list price must be sufficient to cover print cost and distribution fees;
- eligible print projects may be sent to Amazon and Ingram/LSI, subject to format/content requirements and downstream acceptance.

This architecture is convenient but structurally lower-margin than a direct sale because the retail/distribution channel takes a large share before creator revenue.

### Lulu Direct
Lulu Direct is a direct-to-consumer POD/fulfillment architecture. Current Lulu materials support Shopify, WooCommerce, Wix, API workflows, order import, and newer direct buy/checkout tools.

For ecommerce integrations, Lulu describes **two transactions**:
1. retail sale between customer and merchant;
2. fulfillment transaction between merchant and Lulu.

The merchant receives customer revenue (less applicable payment/platform fees) and Lulu charges for manufacturing/fulfillment/shipping. Lulu prints, packages and ships the book to the customer on demand.

## 2. Merchant-of-record / tax boundary
The phrase “Lulu Direct” does not by itself establish one universal merchant-of-record allocation.
- In Shopify/Wix/WooCommerce/API-style integrations, the merchant controls the storefront/customer transaction and pays Lulu for fulfillment.
- Lulu's Direct Buy Button / Direct Checkout documentation states Stripe processes payment and Lulu handles checkout, tax collection, shipping and fulfillment on behalf of the seller.

Because checkout architecture changes responsibility for tax calculation, refunds, customer communications, chargebacks and records, Ekewaka must validate the exact implementation and obtain CPA/tax review before treating tax/GRT responsibility as settled.

## 3. Inventory and fulfillment
Lulu Direct is POD: products are manufactured for each order rather than pulled from stocked publisher inventory. This can eliminate warehouse carrying cost and reduce unsold-inventory exposure, but per-unit manufacturing and shipping normally remain higher than optimized large-run printing.

Current Lulu materials describe global production/fulfillment to more than 200 countries/territories and white-label shipping capabilities. Delivery estimates depend on product, print facility, destination and carrier and are not guaranteed.

## 4. Bulk economics
Current Lulu pricing help states:
- no minimum order;
- automatic bulk discount begins at **100 copies**;
- **100–499 copies receive a 5% discount**;
- **500+ copies require a custom quote**.

Therefore:
- 1–99: use base calculator manufacturing cost;
- 100–499: model 5% manufacturing discount where applicable;
- 500+: do not infer a discount; require live quote.

## 5. Global Distribution eligibility constraints
Lulu's August 2026 exclusions page states some formats/specifications are not eligible with Amazon and/or Ingram. It also states that coloring books, journals, diaries, puzzle books, study guides, workbooks, and books with many blank/lined pages are not accepted for Global Distribution through the cited Amazon/Ingram path. Some Lulu-manufacturable products may therefore be suitable for direct sales but not broad retail distribution.

This is especially relevant to Ekewaka workbooks/premium products: direct Lulu fulfillment may remain possible even where Global Distribution is restricted.

## 6. Direct economics model
For every direct order, FR-WP-06 should model:

`customer receipts - payment processing - ecommerce/platform fee - print cost - fulfillment fee - outbound shipping subsidy - refunds/chargebacks - customer support - tax/GRT effects = direct contribution before author royalty/overhead`

Do not compare direct contribution with Ingram/KDP royalties without normalizing all omitted costs.

## 7. Direct stocked-inventory alternative
Lulu Direct is not the only DTC path. Ekewaka may also procure short-run/offset inventory and fulfill:
- internally;
- through a local fulfillment partner;
- through a 3PL;
- through a printer/fulfillment vendor such as Bookmobile.

Stocked inventory may lower manufacturing cost at volume but adds warehouse, pick/pack, shrink/damage, insurance, inventory accounting, cash tied in stock, and obsolescence risk.

## 8. Risks / unresolved items
- Exact Lulu manufacturing and shipping costs require title/destination calculator runs.
- Direct checkout merchant/tax/GRT treatment requires implementation-specific review.
- Customer return/refund policy remains a later governance/legal/commerce decision.
- Global Distribution exclusions may make some workbook/specialty titles direct-only.
- Direct sales increase customer-data/privacy and support obligations.

## Primary sources
- https://help.lulu.com/en/support/solutions/articles/64000255464-creator-revenue-the-basics
- https://help.lulu.com/en/support/solutions/articles/64000262744-creator-revenue-guide
- https://help.lulu.com/en/support/solutions/articles/64000255458-how-do-i-set-a-retail-price-for-my-print-book
- https://help.lulu.com/en/support/solutions/articles/64000255597-publishing-a-print-book-for-global-distribution
- https://help.lulu.com/en/support/solutions/articles/64000267552
- https://www.lulu.com/sell
- https://help.luludirect.lulu.com/en/support/solutions/articles/64000311712-direct-checkout-information
- https://help.luludirect.lulu.com/en/support/solutions/articles/64000311814-how-does-lulu-direct-merchant-pricing-work-
