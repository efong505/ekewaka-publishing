# FR-WP-04 — Lane C Rights, Account & ISBN Boundary Analysis

**Retrieval date:** 2026-09-15

## 1. Governing boundary

The accepted FR-WP-05 foundation controls this analysis. For **Lane C — fee-for-service author services**, the safer default is:
- the customer remains their own publisher;
- the customer retains copyright and publishing rights;
- Ekewaka receives only narrow permissions necessary to perform purchased services;
- the customer controls publisher identity and ISBNs where an ISBN is used;
- the customer controls distribution/retailer accounts where practicable;
- book-sale revenue flows directly to the customer where practicable.

This differs from Lane A, where Ekewaka is the publisher of accepted editions, and from Lane B, which remains research-only.

## 2. Competitor evidence

### Gatekeeper Press

Gatekeeper publicly states that authors retain:
- 100% of rights;
- ISBNs Gatekeeper assigns;
- created files after full payment;
- 100% of royalties/control.

At the same time, Gatekeeper's FAQ indicates that an author can establish their own imprint/publisher identity; absent that setup, Gatekeeper may be listed as publisher in relevant metadata.

**Finding:** copyright/right retention does not by itself answer publisher-of-record, imprint or metadata-control questions.

### Destiny House Publishing

Destiny House states that authors maintain 100% of publishing rights and set retail price, while its packages include an ISBN/barcode.

**Finding:** a service provider can market strong author-rights retention while ISBN ownership/publisher-record details still require explicit contractual and metadata analysis.

### BookBaby

BookBaby publicly emphasizes author retention of rights and creative/financial control in a full-service self-publishing model.

**Finding:** useful directional comparator, but exact account/identifier treatment must be validated at transaction level before modeling it as equivalent to customer-controlled accounts.

### Ebook Launch

Ebook Launch's print-formatting service does not supply an ISBN; it can place a customer-provided ISBN in the production file.

**Finding:** design/formatting can remain cleanly separated from identifier ownership.

## 3. Recommended Lane C control matrix — research recommendation only

| Control | Preferred Lane C default |
|---|---|
| Copyright | Customer |
| Publishing rights | Customer; only narrow service permission to Ekewaka |
| Publisher of record | Customer / customer-selected imprint |
| ISBN | Customer-controlled when required |
| KDP/Ingram/retailer accounts | Customer-controlled where practicable |
| Metadata approval | Customer approval for identity/commercial fields |
| Final production files | Delivered to customer per agreement |
| Source/editable files | Delivery explicitly defined by service scope |
| Book-sale revenue | Direct to customer where practicable |
| Provider access | Least-privilege, documented, removable at closeout |
| Sales/placement promises | None |
| Lane A acquisition | Separate process; payment for Lane C never implies acquisition |

## 4. ISBN-support boundary options for later design

Potential service levels, without Ekewaka purchasing an ISBN for the customer:
1. written ISBN/publisher-identity guidance;
2. checklist for customer self-acquisition;
3. screenshare/coaching while customer performs the transaction;
4. metadata-preparation assistance using customer-controlled identifiers;
5. bounded administrative assistance only after counsel validates agency/account-control terms.

Ekewaka should **not** default to using an Ekewaka publisher ISBN for a Lane C client, because that would blur publisher-of-record identity and `RISK-002` controls.

## 5. Account-access controls

If later approved, operational controls should include:
- customer-owned primary email/account where supported;
- MFA retained by customer;
- delegated/sub-user access rather than credential sharing where supported;
- access register;
- least privilege;
- no reuse of customer credentials;
- documented offboarding/revocation;
- exported final metadata and files;
- no retention of access beyond the contracted support window without explicit authorization.

## 6. Counsel-review questions

Before Lane C launch, publishing/business counsel should review:
- narrow service-license language;
- customer warranties and permissions responsibility;
- account-access agency language;
- ISBN/publisher-of-record representations;
- source-file/IP ownership and third-party asset licenses;
- AI-assisted content/artwork disclosure and rights;
- termination/offboarding;
- refund/change-order language;
- marketing disclaimers and consumer-protection posture.

No legal conclusion or final contractual term is adopted by this artifact.
