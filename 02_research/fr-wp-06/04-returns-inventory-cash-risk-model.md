# FR-WP-06 — Returns, Inventory and Cash-Risk Model

## Returns
No universal return rate is asserted. Define `r` as modeled return rate and test low/base/high/stress cases.

Trade expected-value formulation:
`Expected contribution = recognized wholesale receipts − manufacturing − r×return chargeback basis − r×return handling/shipping − royalty on contractually eligible net sales − other variable costs`.

For Ingram Yes-Deliver, the accepted feeder records wholesale-cost chargeback plus a current U.S. `$3` handling amount per returned book; non-U.S. handling and current policies require live recheck. Yes-Destroy removes return shipping/handling but not wholesale-cost exposure.

## Inventory
`Inventory cash committed = units ordered × landed unit cost + inbound freight + setup/proofs`.
`Expected unsold units = units ordered − expected sell-through`.
`Carrying cost = average inventory × carrying-rate × time`, where carrying-rate is a planning variable.
Add storage, receiving, pick/pack, shrink, damage, obsolescence, and disposal/remainder costs as separate parameters.

## Cash conversion
Track sale/order, manufacturing payment, freight payment, inventory receipt, channel report, publisher receipt, return charge, reserve release, royalty accrual, and royalty payment dates.

## Reserve structure
`Return reserve = exposed trade receipts × modeled return sensitivity + modeled handling/freight exposure`.
`Inventory reserve = at-risk unsold inventory + shrink/damage/obsolescence provision`.

No reserve percentage is approved. Reserve levels remain analysis/recommendation inputs for Human Owner decision after verification.
