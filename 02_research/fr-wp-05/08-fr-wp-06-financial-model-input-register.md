# FR-WP-05 — FR-WP-06 Financial Model Input Register

FR-WP-06 may consume these as **research inputs**, not approved financial terms.

| Input category | Required model treatment | Status |
|---|---|---|
| ISBN acquisition | Scenario by quantity/block; live Bowker price capture before decision | Open/live recheck |
| Identifier consumption | Per title × format × edition/revision assumptions | Ready as parameter |
| Platform-provided ISBN | $0 acquisition scenario plus portability/publisher-identity constraint | Ready as scenario only |
| Metadata administration | Labor/time for initial setup, QA, corrections, channel reconciliation | Estimate required |
| Edition/revision cost | New ISBN + setup/proof/distribution revision costs when a new product is required | Parameterize |
| Publisher migration | Potential new ISBN/relisting/reprint/reproof costs | Parameterize |
| Rights review | Publishing/IP counsel budget category | Quote required |
| Permissions | Third-party permission/license cost category | Title-dependent |
| Print rights economics | Royalty base/rate as configurable inputs, not approved values | Pending FIN/counsel/Human Owner |
| Ebook rights economics | Separate configurable assumptions | Pending |
| Audio rights economics | Separate configurable assumptions including production/licensing | Pending |
| Translation/subsidiary rights | Optional revenue/cost modules; no assumption of ownership | Pending rights architecture |
| Territory | Revenue/cost scenarios by licensed territory and channel | Pending contract decisions |
| Term/reversion | Time horizon and post-reversion wind-down costs | Counsel-dependent |
| Audit/accounting | Royalty statement, audit trail, reconciliation labor/system costs | SYS/ROY dependency |
| Channel accounts | Account/setup/maintenance costs and ownership dependencies | Live platform recheck |
| Barcode | Treat as production asset/cost where applicable; do not assume ISBN purchase requires paid barcode | Channel/production dependent |

## Modeling rule
FR-WP-06 must preserve a distinction between:
1. verified current external rates;
2. estimates;
3. configurable business assumptions;
4. Human Owner-approved terms.

FR-WP-05 does not set royalty rates, advances, recoupment terms, package pricing or rights valuations.