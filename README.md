# SOL/USDC Paper-Trading Bot — Public Dashboard

**PAPER TRADING ONLY. Not financial advice.** No private keys, no signing, no real funds.

- Live dashboard: https://abhishekmoore.github.io/solana-paper-bot-dashboard/
- 24h session: 2026-11-03 18:36 IST → 2026-11-04 18:36:11 IST (13:06:11 UTC), $100 simulated starting capital.
- Prices: real public SOL/USD(C) spot (Jupiter, Coinbase fallback), read-only. **Trade quotes are modeled** from that price (not real Raydium/Orca quotes); fees/slippage are simulated.
- Every entry is verified (token validity, balance, quote age, max slippage) before a simulated fill; rejections are shown with the failed check.
- This repo is a static snapshot, auto-published every ~5 minutes from the bot host. GitHub Pages/CDN can lag a few minutes.
- Also: `replay.html`, `dashboard.html`, `quantstats_report.html` (synthetic-data replay); `live_quantstats_report.html` and `live_summary.json` appear after the session ends.
