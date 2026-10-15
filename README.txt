OTC Candle Lab — Prototype

Open index.html in a modern browser.

Current features:
- Import a CSV containing open, high, low, close columns (time is optional).
- Heuristic two-candle forecasts, confidence estimates, and price trace.
- Log forecasts before the outcome, resolve them when later candles are imported, and export the ledger to CSV.
- Synthetic demo data for testing the interface only.

Important limitations:
- Demo data is synthetic, not Quotex data.
- Confidence is heuristic and not a calibrated probability.
- This prototype does not directly connect to Quotex. A normal website cannot read a separate Quotex tab due to browser security boundaries. A direct integration needs an authorized, permitted data/export interface and must be separately implemented and reviewed.
- No guaranteed accuracy or automatic trade execution.
