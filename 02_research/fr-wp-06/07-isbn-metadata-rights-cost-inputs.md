# FR-WP-06 — ISBN, Metadata and Rights Cost Inputs

## Cost architecture
| Category | Model treatment | Status |
|---|---|---|
| ISBN acquisition | quantity/block scenario | live Bowker recheck + Human Owner purchase gate |
| Identifier consumption | title × format × edition/revision | parameterized |
| Platform-provided ISBN | `$0` acquisition scenario with portability/publisher-identity constraint | scenario only |
| Metadata setup/QA | labor hours per product/channel | estimate required |
| Corrections/reconciliation | labor + relisting/reproof | parameterized |
| Founding-catalog migration | provenance review + possible new ISBN/relisting/reprint | unresolved/title-specific |
| Counsel | budget category | quote required |
| Permissions/licenses | title-specific | unresolved |
| Audit/accounting | systems + reconciliation labor | future SYS/ROY dependency |
| Reversion/wind-down | relisting, inventory, metadata, accounting closeout | counsel/contract dependent |

## Identifier consumption formula
`ISBN demand = Σ(unique ISBN-requiring title-format-edition products) + governed contingency`, with no ISBN reuse.

No Bowker block size, barcode purchase, publisher-of-record architecture, account owner, rights valuation, royalty, territory, term, or reversion term is approved.
