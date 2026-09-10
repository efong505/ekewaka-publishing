# FR-WP-03 — Returns, Discounts, and Wholesale Risk Analysis

**Retrieval date:** 2026-09-10

## 1. Core distinction
Wholesale discount and returnability are separate economic controls. A higher wholesale discount can improve retailer economics and ordering acceptance but reduces publisher compensation. Returnability can improve bookstore willingness to order but creates contingent publisher liability after the original sale.

## 2. Ingram trade exposure
Current Ingram guidance presents **55%** as the standard trade-oriented wholesale discount for bookstore access. At a $20 list price, a 55% discount leaves a $9 wholesale amount before print cost and applicable fees.

If a book is returnable, Ingram states the publisher is charged the current wholesale cost when the return is processed. Under current published terms:
- Yes-Destroy: wholesale cost charged back; no return shipping/handling.
- Yes-Deliver: wholesale cost charged back plus $3/book to U.S. return addresses or $20/book to non-U.S./international addresses.
- No: no returns accepted through Ingram, but bookstore stocking/order willingness can be reduced.

The key financial consequence is that a publisher can show positive sales compensation and later incur negative return charges. Returns therefore create both P&L and liquidity risk.

## 3. KDP Expanded Distribution
KDP Expanded Distribution uses a fixed **40% of list price less print cost** publisher royalty model for eligible paperbacks. KDP does not expose the publisher to selecting a bookstore wholesale-discount percentage or direct trade-returnability option in the same way Ingram does. This simplifies the publisher-side economic model but provides less trade-channel control and generally lower contribution than Amazon-native KDP sales.

## 4. Return reserve design for FR-WP-06
No universal return-rate percentage is established by this work package. FR-WP-06 should model return rate as a sensitivity by title/channel, for example:
- low-return case;
- base planning case;
- high-return stress case.

Reserve logic should be linked to **wholesale value subject to chargeback**, plus Yes-Deliver handling where applicable, rather than only to print cost.

Suggested model fields:
- gross units shipped/sold into trade;
- wholesale value per unit;
- assumed return percentage;
- timing lag to return;
- destroy vs deliver election;
- return handling/shipping per unit;
- reserve opening balance;
- reserve additions/releases;
- net cash compensation after returns.

Exact percentages remain an FR-WP-06 modeling decision and later operating-policy gate.

## 5. Discount sensitivity
FR-WP-06 should test at least three Ingram wholesale-discount scenarios:
- lower-discount / margin-preservation case;
- intermediate case;
- 55% trade-oriented case.

It should then pair those with returnability scenarios because the economic interaction is material. A 55% discount plus high returns can make a title uneconomic even if direct/Amazon sales are profitable.

## 6. Bookstore/library implications
- Trade-friendly terms can increase ordering acceptability but do not guarantee placement.
- Returnable status can reduce retailer risk but transfers risk to the publisher.
- Non-returnable status can preserve publisher downside but may reduce stocking willingness.
- Library acquisition may occur through wholesalers without requiring the same front-table bookstore economics, so bookstore and library channels should not be treated as identical demand patterns.

## 7. Direct sales comparison
Direct sales avoid a conventional wholesale discount, but they add other costs: payment processing, ecommerce fees, pick/pack or POD fulfillment, postage, shipping subsidy, customer returns/refunds, chargebacks, customer service, and tax/GRT administration. The absence of a 55% wholesale discount is not equivalent to a 55-point margin improvement.

## 8. Policy boundary
DIST-01 does **not** select a final wholesale discount or returns policy. Any final policy must follow FR-WP-06 economics, channel strategy, professional review as needed, and Human Owner approval where material.

## Primary sources
- https://www.ingramspark.com/blog/how-to-sell-your-book-to-bookstores
- https://www.ingramspark.com/blog/making-your-book-returnable
- https://www.ingramspark.com/blog/why-should-i-discount-my-book
- https://www.ingramspark.com/hubfs/downloads/user-guide.pdf
- https://kdp.amazon.com/en_US/help/topic/GQTT4W3T5AYK7L45
