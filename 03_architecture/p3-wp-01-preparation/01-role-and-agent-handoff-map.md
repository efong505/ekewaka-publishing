# P3-WP-01 — Role and Agent Handoff Map

| Role | Bounded responsibility | Handoff |
|---|---|---|
| PM-01 | Sequencing, integration, authoritative state, gates | Integrates specialist outputs; routes to VER-01 and Human Owner |
| ACQ-01 | Acquisition intake/evaluation/memo and author-relations architecture | FIN-01 economics; RIGHTS-01 rights; LEGAL/CONTRACT where material; PM-01 |
| PROD-01 | Editorial, production, file/proof/change control, QC, release readiness | RIGHTS-01/DIST-01 coordination; PM-01 |
| RIGHTS-01 | ISBN/edition decision architecture, metadata, rights, permissions/provenance registries | ACQ/PROD/DIST/LEGAL; no ISBN purchase/assignment |
| DIST-01 | Printing/distribution/fulfillment decision architecture | FIN-01 economics; RIGHTS/PROD channel dependencies; no vendor commitment |
| ROY-01 | Ledger, statements, reserves, reconciliation, payment-approval and audit architecture | FIN-01 validation; PM-01; no production deployment/payment |
| FIN-01 | Title/company economics where material | Supports ACQ/DIST/ROY; does not self-certify |
| LEGAL-01 / CONTRACT-01 | Legal research, agreement categories, counsel routing, version/signature controls | Qualified counsel where material; no execution |
| VER-01 | Independent review | Must not author and verify same high-impact artifact |

Workstreams may run in bounded parallel after execution authorization where dependencies permit. PM-01 integrates before VER-01. No specialist self-verifies; ACQ-01 may recommend but not authorize an offer or acquisition.
