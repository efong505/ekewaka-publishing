# FR-WP-02 — Lane A: Trade-Publishing Economics Benchmark

**Retrieval date:** 2026-09-08  
**Purpose:** Industry/economic benchmark only. No royalty, advance, acquisition, or contract term is approved here.

## 1. Economic identity

Lane A is a publisher-funded acquisition model. The author does not pay Ekewaka to publish the work. Ekewaka would fund approved editorial, design, production, metadata/distribution setup, proofs and approved marketing, and would recover that investment from publisher revenue over the title lifecycle.

The economic obligation therefore falls on the publisher to reject titles whose probable contribution cannot support title investment, overhead, author compensation, returns exposure and cash-flow timing.

## 2. Royalty benchmarks

The Authors Guild Model Trade Book Contract provides a current benchmark framework:

- hardcover: 10% of list price on the first 5,000 copies, 12.5% on the next 5,000 and 15% thereafter for a major-publisher style structure;
- for many small and medium-sized publishers, the Guild identifies net receipts as a common royalty base and presents the same 10% / 12.5% / 15% escalation on net receipts as a model;
- the Guild states that most traditional publishers currently pay authors 25% of publisher net receipts for ebooks;
- the Guild model gives at least 25 free hardcover copies and 25 paperback copies, with additional author copies often around a 50% discount or cost-plus-shipping structure.

Source: https://go.authorsguild.org/contract_sections/5 and https://go.authorsguild.org/contract_sections/18

These are **benchmarks, not Ekewaka terms**. A new small press using POD, wholesale distribution and direct sales must test royalty bases against actual channel compensation. A list-price royalty can become relatively costly in a channel with a deep wholesale discount. A net-receipts royalty tracks publisher cash more closely but only if “net receipts” is tightly and transparently defined.

## 3. Advance / no-advance economics

Trade publishing can include advances against future royalties, but an advance is additional publisher working-capital risk. Ekewaka’s master-prompt concept of beginning with $0 advance / royalties from first sale is economically plausible for a new small press, but remains a policy and contract decision for later review.

FR-WP-06 should model at least:

- $0 advance;
- small selective advance;
- advance recoupment timing;
- effect of advance on title break-even and cash runway.

No advance policy is approved by FR-WP-02.

## 4. KDP Amazon print benchmark

KDP’s current paperback terms state that Amazon marketplace sales generate either 50% or 60% of list price, depending on list price and marketplace, less printing cost. On Amazon.com, the 60% tier starts at $9.99. Expanded Distribution generates 40% of list price less printing cost.

Formula:

`Publisher-account compensation = royalty-rate × list price − print cost`

KDP’s own example for a $15, 333-page black-ink paperback uses a $5 print cost and yields:

- Amazon standard: `0.60 × 15 − 5 = $4.00`
- Expanded Distribution: `0.40 × 15 − 5 = $1.00`

Source: https://kdp.amazon.com/en_US/help/topic/G201834330

This is not Ekewaka profit. From that compensation Ekewaka would still need to support author royalty, title investment, overhead and any other title-specific cost.

KDP also states that POD requires no print inventory up front. This reduces inventory risk but does not remove title-investment risk.

## 5. Ingram/trade benchmark

IngramSpark’s publisher compensation calculator uses:

- format/specification;
- list price;
- wholesale discount;
- print economics;

to determine publisher compensation. Ingram’s public guidance makes clear that a larger wholesale discount decreases publisher compensation but affects trade attractiveness. Returnable status creates additional downside: returned books can be charged back against publisher compensation, with additional shipping/handling exposure under return-to-publisher treatment.

Sources:

- https://myaccount.ingramspark.com/Portal/Tools/PubCompCalculator
- https://www.ingramspark.com/blog/making-your-book-returnable

FR-WP-03 must establish the current operational discount/returnability choices before FR-WP-06 treats them as final assumptions.

## 6. Returns exposure

Traditional bookstore economics differ from Amazon POD because returnability can reverse prior revenue. A small press should therefore distinguish:

- **gross shipped units** from **net sold units**;
- recognized publisher compensation from cash subject to later returns;
- nonreturnable/direct channels from returnable trade channels.

FR-WP-06 should include a return-reserve variable and stress cases rather than assuming zero returns for trade distribution.

## 7. Direct-sales benchmark

Direct sales can materially increase contribution by replacing a wholesale/retailer deduction with payment processing and fulfillment costs.

Lulu Direct’s current model demonstrates the structure: the customer purchases from the publisher/merchant; the merchant separately pays Lulu for printing, fulfillment, shipping and taxes. Lulu’s published example is:

- customer price: $22.00
- print: $5.00
- shipping/handling: $5.75
- fulfillment fee: $1.75
- remaining amount before merchant payment/platform/support/marketing overhead: $9.50

Source: https://help.luludirect.lulu.com/en/support/solutions/articles/64000270795-how-are-lulu-direct-prices-calculated-and-what-will-i-pay-

This shows why FR-WP-06 should calculate **direct contribution separately** rather than using a blended average with Amazon or Ingram.

## 8. Author-copy economics

Author copies can be handled several ways:

- free contractual copies included in publisher investment;
- copies sold at print cost plus shipping;
- copies sold at a defined discount from list;
- bulk tiers.

The Authors Guild model recognizes free copies and additional discounted purchases. For Ekewaka, author-copy pricing should not become an undisclosed publisher profit center that distorts author relations, but it also should not create an unmodeled loss. FR-WP-06 should separately model:

`author-copy charge − print − inbound/outbound shipping − handling/admin = contribution`

and test whether author-copy sales earn royalties under the eventual contract.

## 9. Subsidiary rights

The Authors Guild model treats subsidiary-rights income separately and allocates the author a negotiated share of publisher net proceeds. The economic principle for Ekewaka is that rights not actively exploited should not be acquired merely for theoretical value. Rights scope and splits require publishing-counsel review and later RIGHTS-01/contract architecture.

Source: https://go.authorsguild.org/contract_sections/6

## 10. Small-press break-even drivers

Minimum variables for every Lane A title:

1. list price by format;
2. actual channel compensation formula;
3. print/manufacturing cost;
4. wholesale discount;
5. return rate/reserve;
6. author royalty base/rate;
7. editing;
8. cover/interior/ebook production;
9. proofs and initial copies;
10. marketing/publicity budget;
11. ISBN/metadata/administration allocation;
12. overhead allocation;
13. cash timing;
14. direct/bulk mix;
15. expected unit volume.

Break-even should be calculated from **contribution per net unit**, not list price.

## 11. Preliminary Lane A conclusion

**Supported for later architecture with conservative controls.**

Lane A best matches the selective publishing mission, but economics must be title-specific. POD can reduce inventory exposure, direct sales can improve contribution, and no-advance deals can reduce working-capital requirements, but none of these eliminates acquisition risk. FIN-01 recommends no outside-author offer until FR-WP-06 supplies a validated acquisition P&L and minimum acceptable margin/runway rules.
