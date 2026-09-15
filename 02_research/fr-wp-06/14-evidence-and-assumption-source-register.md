# FR-WP-06 — Evidence and Assumption Source Register

## Governing sources
| ID | Source | Use |
|---|---|---|
| GOV-01 | `18_handoffs/fr-wp-06-fin-01-foundational-financial-model-launcher.md` | scope, outputs, gates, lifecycle |
| GOV-02 | `00_governance/work-package-register.md` | feeder acceptance/current state |
| GOV-03 | `00_governance/human-owner-gates.md` | execution authority boundaries |
| GOV-04 | `00_governance/risk-register.md` | active project risks |
| GOV-05 | `01_agents/fin-01-publishing-business-model-finance-agent.md` | FIN-01 role/boundaries |

## Accepted feeder sources
| ID | Source | Key inputs |
|---|---|---|
| F02-01 | `00_governance/fr-wp-02-pm-acceptance.md` | accepted-with-conditions status; volatile-economics recheck; Lane B/C controls |
| F02-02 | `02_research/fr-wp-02/07-fr-wp-06-financial-model-input-register.md` | payout benchmarks, author-economics benchmarks, Lane A/B/C variables, cash fields |
| F03-01 | `00_governance/fr-wp-03-pm-acceptance.md` | vendor/live-quote, returns, CPA/GRT, 3PL conditions |
| F03-02 | `02_research/fr-wp-03/08-fr-wp-06-financial-model-input-register.md` | KDP/Ingram/Lulu mechanics, volume anchors, returns/inventory fields |
| F05-01 | `00_governance/fr-wp-05-pm-acceptance.md` | rights/ISBN/account-control conditions |
| F05-02 | `02_research/fr-wp-05/08-fr-wp-06-financial-model-input-register.md` | identifier, metadata, rights, migration, counsel/audit cost architecture |

## Modeled assumptions used for arithmetic demonstrations
| Assumption | Value | Status |
|---|---:|---|
| Reference paperback list price | $18.99 | MPA/HODV; not approved |
| Synthetic common manufacturing for cross-channel arithmetic | $4.60 | MPA using accepted KDP example; not a cross-vendor quote |
| Direct processor | 3% + $0.30 | MPA; provider not selected |
| Direct fulfillment | $2.50/order | MPA; provider not selected |
| Base channel mix | 50% KDP / 30% Ingram-style / 20% direct | MPA |
| Base trade return sensitivity | 15% | MPA; not evidence-backed universal rate |
| Base illustrative royalty | 10% of defined publisher net receipts | MPA/HODV; not approved contract term |
| Base fixed title investment | $8,000 | MPA; not budget approval |
| Downside/base/upside/stress weighted contribution | $1.75 / $5.25 / $8.00 / $0.50 | MPA sensitivity outputs |

## Provenance rule
Any future replacement of a placeholder must record source, retrieval/effective date, scope/title specification, currency/tax/freight treatment, and whether the value is quoted, contractual, observed, benchmarked, or modeled. Volatile vendor/platform values require live recheck before material use.
