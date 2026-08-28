# Digital Asset Trading Operations Control Center

A simulated middle office operating tool for a multi-venue market maker.

**Live:** https://justinthomcrypto.github.io/Auros/

## Exchange Reconciliation
Internal book vs exchange and on-chain records across six controls: balances,
positions, trades, fees, funding, and transfers. Break queue with severity,
age, probable cause, and resolution owner. Five-state transfer pipeline with
per-leg timers. Daily exception report.

## Financing Ledger
Credit facilities by lender, asset, rate, and accrual basis. Drawdown ledger
with accrued interest. Lender invoices reconciled against internal accrual.
Payment schedule with whitelist, network, and approval verification.

## Notes
Single HTML file, no dependencies or build step. All data is synthetic and
generated in the browser.

Justin Thom, 2026
