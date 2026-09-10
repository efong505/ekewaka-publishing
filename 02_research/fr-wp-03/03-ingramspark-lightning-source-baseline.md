# FR-WP-03 — IngramSpark / Lightning Source Baseline

**Retrieval date:** 2026-09-10  
**Evidence class:** Current IngramSpark primary sources unless labeled benchmark/model assumption.

## Current verified mechanics
IngramSpark's publisher-compensation model is driven by list price, wholesale discount, printing cost, and current applicable fees. Its live Publisher Compensation Calculator asks for title specifications, list price, and discount and returns an estimated compensation amount.

A simplified public formula used in Ingram materials is:

`list price - (wholesale discount × list price) - printing cost = publisher compensation`

Current Ingram materials also reference a **market access fee** deducted from the wholesale amount, so a live calculator/account quote must supersede simplified examples before FR-WP-06 hard-codes compensation.

## Wholesale discount
- Ingram's current bookstore guidance says an industry-standard trade-oriented wholesale discount is typically **55%**.
- Current guidance explains that 55% allows the downstream retailer to receive a customary trade margin after the wholesaler's share.
- Older/currently accessible Ingram setup guidance describes U.S./Canada discount settings in the **40%–55%** range, with international markets as low as 35% depending on market.
- A lower discount can increase publisher compensation but may reduce bookstore willingness to stock/order.

Therefore FR-WP-06 must model discount as a sensitivity, not a single fixed assumption.

## Returns
IngramSpark currently supports:
1. **No / Non-Returnable** — Ingram does not accept bookstore returns for the title.
2. **Yes — Deliver** — returnable; publisher receives physical returned copy where available.
3. **Yes — Destroy** — returnable; returned copies are destroyed.

Current Ingram guidance states publishers are charged the **wholesale cost** of returned books. For **Yes — Deliver**, current published return shipping/handling is **$3.00 per book to U.S. addresses** and **$20.00 per book to non-U.S./international addresses**. Yes-Destroy charges the wholesale cost but no return shipping/handling fee.

Ingram explicitly warns that many brick-and-mortar stores prefer or require returnability. Returnability may improve stocking consideration but can create large negative cash-flow reversals. Books may be returned after the original sale, and publisher compensation reports reflect negative return amounts.

## Trade example — verified structure, modeled title
For a modeled `$20.00` list price at a `55%` wholesale discount, the wholesale amount available before printing/fees is `$9.00`. That does **not** mean $9.00 contribution: print cost and applicable Ingram fees still reduce publisher compensation. A return at the same wholesale basis can charge back approximately `$9.00` before any Yes-Deliver handling charge.

This example demonstrates why a return reserve must be modeled on **wholesale value**, not only manufacturing cost.

## Bookstore/library availability
Ingram's central value is trade discoverability/orderability through established distribution infrastructure. Current Ingram guidance emphasizes bookstore ordering convenience and identifies availability through Ingram as a meaningful prerequisite for many stores. This does not guarantee placement, sell-through, or institutional purchasing.

## Publisher orders / direct use
Ingram provides a live **Print and Ship Calculator** for publisher orders shipped to the publisher or customers. Title-specific manufacturing and shipping depend on book type, trim, specs, quantity, printing location and destination. These should be captured as live quote evidence for representative Ekewaka formats before any procurement decision.

## Global production
Ingram's Global Connect materials describe localized manufacturing through partner facilities as a way to reduce international freight/inventory requirements. Drop-ship restrictions and print-signature differences can apply by market, so international production must be validated by title and destination.

## FR-WP-06 sensitivity set
At minimum model:
- wholesale discounts: low / mid / 55% trade-oriented;
- returnability: No / Yes-Destroy / Yes-Deliver;
- low/base/high return rates;
- return reserve based on wholesale value;
- current print cost and market-access fee;
- publisher-order landed cost for direct/event inventory;
- trade cash timing and returns timing;
- list-price sensitivity required to preserve minimum contribution.

## Risks
- `RISK-007` is directly material: returns can create chargebacks after prior sales.
- `RISK-010`: publisher may owe return costs during periods of weak new sales.
- Trade-friendly 55% terms can materially compress contribution on high-page-count or color books.
- Non-returnable/lower-discount settings may improve per-unit economics but reduce bookstore acceptance.
- Current fees and print costs are volatile and require recheck before pricing/contracting.

## Primary sources
- https://myaccount.ingramspark.com/Portal/Tools/PubCompCalculator
- https://myaccount.ingramspark.com/Portal/Tools/ShippingCalculator
- https://www.ingramspark.com/blog/how-to-sell-your-book-to-bookstores
- https://www.ingramspark.com/blog/making-your-book-returnable
- https://www.ingramspark.com/blog/why-should-i-discount-my-book
- https://www.ingramspark.com/hubfs/downloads/user-guide.pdf
- https://www.ingramspark.com/plan-your-book
- https://www.ingramspark.com/blog/reach-the-world-with-global-connect
