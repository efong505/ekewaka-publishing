# FR-WP-06 — Foundational Financial Model Report

**Agent:** FIN-01 — Publishing Business Model / Finance Agent  
**Starting baseline:** `649ef0de7d0bff55fb819c725d02f484458d79dd`  
**Lifecycle:** FIN-01 EXECUTION COMPLETE — REVIEW PENDING  
**Purpose:** auditable foundational modeling only; not verified, PM accepted, or Human Owner approved.

## 1. Scope completed
This package builds a source-traceable model architecture for Lane A title economics, channel economics, returns/inventory/cash risk, Lane B research-only sensitivities, Lane C service cost architecture, ISBN/metadata/rights costs, company-level operating structure, scenario testing, break-even, margin, and reserve analysis.

It consumes accepted FR-WP-02, FR-WP-03, and FR-WP-05 research while preserving every live-recheck, professional-review, vendor-validation, legal/tax, account-control, and Human Owner gate. FR-WP-04 remains PLANNED and is not treated as completed.

## 2. Modeling standard
Every material input is one of: verified current source input; accepted upstream research input; modeled planning assumption; Human Owner decision variable; unresolved/professional-review input.

Core formulas:
- `channel cash revenue/unit = list price × applicable payout/share`, where the upstream evidence supports a percentage model.
- `unit contribution = channel cash revenue − manufacturing − channel/fulfillment costs − expected returns cost − modeled royalty − other variable cost`.
- `title break-even units = title fixed cash investment / weighted unit contribution`, when weighted contribution is positive.
- `contribution margin % = contribution / recognized revenue`.
- `minimum cash reserve scenario = operating reserve + title cash-at-risk + return/inventory reserve + contingent professional/vendor reserve`.

No formula converts an unresolved input into a fact.

## 3. Illustrative reference arithmetic
To make the model independently auditable, a synthetic paperback example uses a **modeled list price of $18.99** (not approved) and the accepted KDP 300-page U.S. B&W **$4.60 benchmark print-cost example** only for demonstration. Using that same $4.60 outside KDP is a synthetic comparability device, not a vendor quote.

Illustrative pre-overhead contribution before author royalty:
- KDP Amazon at 60% tier: `18.99 × 60% − 4.60 = $6.79`.
- KDP Expanded Distribution: `18.99 × 40% − 4.60 = $3.00`.
- Ingram-style 55% wholesale discount, synthetic $4.60 manufacturing: `18.99 × 45% − 4.60 = $3.95` before returns/fees.
- Lulu Global Distribution formula, synthetic $4.60 manufacturing: `(18.99 × 50% − 4.60) × 80% = $3.92`.
- Synthetic direct sale with 3% + $0.30 processing and $2.50 fulfillment assumptions: `18.99 − 4.60 − (18.99×3%+0.30) − 2.50 = $11.02` before royalty, refunds, tax/GRT, shipping subsidy, and overhead.

These values illustrate channel dispersion; they do not approve a retail price, print specification, processor, fulfillment provider, or channel mix.

## 4. Reference planning scenario
A base demonstration uses modeled variables only: 50% KDP Amazon / 30% Ingram-style trade / 20% direct, 10% modeled royalty on defined publisher net receipts, 15% modeled trade return sensitivity, and $8,000 modeled fixed title investment. Under the synthetic arithmetic, weighted contribution is about **$5.25 per gross unit**, producing a modeled break-even of about **1,524 gross units**. This is a sensitivity result, not an acquisition threshold or approved underwriting rule.

## 5. Primary findings
1. Channel mix is a first-order driver: direct contribution can materially exceed trade/POD contribution, but it introduces payment, fulfillment, tax/GRT, customer-service, refund, fraud, and operational obligations.
2. Trade returns can collapse already-thin wholesale contribution; return policy and reserve design must therefore be explicit decision variables.
3. Production investment and author economics jointly dominate Lane A break-even; neither should be hidden in overhead.
4. Lane B can only be modeled as a transparent two-sided risk allocation framework; no package, fee, royalty, or launch is authorized.
5. Lane C requires bottom-up labor/vendor costing and scope-control mechanics before any public package price can be responsibly considered. FR-WP-04 remains a required refinement source for competitive/service-market context.
6. ISBN/metadata/rights costs are structurally small in some scenarios but can become material through multi-format identifier consumption, migration, rights review, permissions, and reconciliation labor.
7. Company-level liquidity should be governed by cash timing and downside exposure, not accounting profit alone.

## 6. Limitations
Representative live title-specific KDP/Ingram/Lulu cost captures, short-run/offset quotes, evidence-backed return-rate calibration, tax/GRT treatment, counsel costs, rights economics, 3PL economics, payment/accounting system costs, insurance, compensation, rent, and actual sales demand remain unresolved. They are parameterized or reserved for recheck.

## 7. Recommendations separated from approvals
Proceed to independent VER-01 review. Before any material pricing, acquisition, print-order, reserve, or Lane C decision, replace placeholders with live validated inputs and retain downside/stress cases. Do not use this package as final pricing, procurement, acquisition, tax, accounting, or rights authority.

## 8. Lifecycle disposition
**FR-WP-06 Complete With Open Professional/Implementation-Validation Items — Ready for Independent Verification**
