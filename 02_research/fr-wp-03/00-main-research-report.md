# FR-WP-03 — Printing, Distribution & Fulfillment Baseline

**Agent:** DIST-01 — Printing, Distribution & Fulfillment Agent  
**Repository:** `efong505/ekewaka-publishing`  
**Branch:** `main`  
**Exact starting baseline:** `2c4b67f0e4f45bd0d83a04e636c53586de32a666`  
**Research retrieval date:** 2026-09-10  
**Lifecycle at completion:** REVIEW PENDING

## 1. Governance and scope
FR-WP-03 is bounded foundational research. It does not select a final printer/distributor, set final retail pricing, wholesale discount, returns policy, purchase ISBNs, place orders, launch Lane B/Lane C, or authorize publication. FR-WP-02 remains PM ACCEPTED — WITH CONDITIONS. DIST-01 preserves all Human Owner gates and does not self-verify.

## 2. Executive findings
1. **KDP Print is strongest as the Amazon-native POD baseline.** Current KDP terms provide 50% or 60% of tax-exclusive list price on Amazon print sales depending on price threshold, less printing cost. On Amazon.com, the 60% paperback tier begins at $9.99. Expanded Distribution pays 40% less printing cost, is paperback-only, and does not guarantee bookstore/library stocking.
2. **IngramSpark is the stronger trade-wholesale availability baseline but transfers real returns risk to the publisher.** Publisher compensation is driven by list price, wholesale discount, print cost, and current fees. Ingram currently presents 55% as the standard trade-oriented wholesale discount. Returnable titles can be charged back at the current wholesale cost; Yes-Deliver also adds return shipping/handling.
3. **Lulu is best treated as two architectures.** Global Distribution uses a channel-fee/gross-profit split. Lulu Direct instead supports direct-to-consumer POD fulfillment where the merchant controls the customer relationship and pays Lulu for manufacturing/fulfillment/shipping. Merchant-of-record and tax responsibility depend on the particular checkout/integration and require implementation review.
4. **Short-run digital fills the gap between POD and offset.** Public vendor evidence supports 10-copy minimums at 48 Hour Books and 25-copy minimums at Bookmobile, with increasing price breaks as quantity rises.
5. **Offset becomes structurally relevant around several hundred copies but only when demand is credible.** PrintNinja publicly states 250-copy minimums for standard hardcover/art-book offset products and lower unit economics at larger quantities. Offset adds prepayment, freight, storage, damage/obsolescence, and sell-through risk.
6. **New Mexico vendors are viable quote targets, not yet validated book-manufacturing partners.** Aiken Printing (Albuquerque) publicly lists offset, short-run digital, perfect binding, inventory/fulfillment and mailing; Starline (Albuquerque) lists offset/digital capacity and custom quotes; Graphic Sky (Santa Fe) lists perfect-bound books; Paper Tiger (Santa Fe) lists books/manuals and mailing. No apples-to-apples public book quote was sufficient to establish unit economics.
7. **Direct sales must be modeled separately.** Direct channels may preserve much more gross revenue than wholesale channels, but the publisher then bears payment processing, customer service, tax/GRT treatment, shipping subsidy choices, refunds/chargebacks, and fulfillment exceptions.

## 3. Working channel architecture for modeling
- **Amazon retail:** KDP Print POD as baseline; no inventory required.
- **Bookstore/library wholesale:** IngramSpark/Lightning Source baseline; discount and returnability treated as explicit sensitivities.
- **Direct ecommerce:** Lulu Direct or separately procured inventory plus fulfillment; channel economics modeled independently.
- **Events/churches/institutions/author copies:** compare KDP author copies, Ingram publisher orders, Lulu bulk, local/regional short-run, and national short-run quotes.
- **Large validated demand:** offset quotation path, with freight/warehouse/carrying-cost model.

This is an architecture recommendation for later modeling, not vendor approval.

## 4. Representative KDP illustration
For a **300-page, regular-trim, black-ink U.S. paperback**, KDP's current published example uses a $4.60 printing cost. At a modeled $15.99 list price:
- Amazon.com at 60%: `(0.60 × 15.99) - 4.60 = $4.99` approximate publisher royalty per sale.
- Expanded Distribution at 40%: `(0.40 × 15.99) - 4.60 = $1.80` approximate publisher royalty per sale.
This is an illustration only. It excludes author royalty, overhead, marketing, taxes, refunds/adjustments, and title investment.

## 5. Volume posture
| Units | Default posture for FR-WP-06 sensitivity |
|---:|---|
| 1 | POD/proof; avoid inventory commitment |
| 10 | POD or 48 Hour Books minimum-run comparison |
| 25 | POD vs Bookmobile/local digital quote |
| 50 | Short-run digital becomes operationally credible for events/bulk |
| 100 | Short-run quote comparison mandatory; Lulu bulk discount begins at 100; 48 Hour Books incentive applies |
| 250 | Compare digital short-run vs offset; PrintNinja offset minimum is relevant for some products |
| 500 | Formal short-run/offset quote comparison; Lulu requires custom quote at 500+ |
| 1,000 | Offset increasingly plausible if sell-through is evidence-backed |
| 5,000+ | Offset/large-run procurement with freight, warehousing and inventory controls; Human Owner bulk-print gate required |

## 6. FR-WP-06 handoff
FR-WP-06 should model separate Amazon POD, Ingram trade, direct POD, direct stocked-inventory, event/bulk, and offset channels. Required variables include list price, print cost, wholesale discount, returns rate/reserve, return shipping, outbound freight, pick/pack, postage, payment processing, platform fees, author-copy policy, inventory carrying cost, shrink/damage, setup/revision fees, payment timing, and author royalty base.

## 7. Material risks
Primary risks are `RISK-003` unsustainable title economics, `RISK-007` distributor/returns exposure, `RISK-010` cash-flow strain, and `RISK-015` vendor/platform dependency. FR-WP-03 adds operational attention to quote comparability, freight volatility, inventory obsolescence, and channel metadata conflicts.

## 8. Open validation items
- Live Ingram print-cost quotes for representative Ekewaka formats and current market-access/account fees.
- KDP author-copy landed cost and shipping for representative destinations.
- Lulu Direct landed fulfillment examples for representative books and destinations.
- Apples-to-apples quotes from at least two New Mexico printers and two national short-run/offset vendors.
- 3PL/warehouse pricing if stocked direct sales are pursued.
- Professional CPA/tax review of direct-commerce merchant/tax/GRT treatment.
- FR-WP-05 resolution of ISBN/metadata/channel-control dependencies.

## 9. Completion posture
The evidence is sufficient for independent verification of the architecture and public platform mechanics, but vendor-specific landed-cost economics remain intentionally open for later quote validation before procurement or FR-WP-06 finalization.
