# Codex instructions — YesTrader Research

- Preserve original user CSV and YesLanguage formula text byte-for-byte. Never delete, overwrite, or silently normalize originals.
- Maintain filename, source, received date (unknown if not verifiable), byte size and SHA-256 for each verified source.
- Separate originals, reconstructed formulas, corrected formulas, candidates, and backtest outputs.
- ON: buy near D0 close; sell at D1 KRX regular-session open.
- TP5: buy near D0 close; sell at first executable +5% target D1–D5, otherwise at D5 close. Do not assume an intraday high touch implies fill.
- Independently evaluate ON and TP5; include costs, slippage, tick size, gaps, execution uncertainty, trade counts, net win rate, median/mean returns, MFE/MAE, worst loss, and signal frequency.
- Avoid future leakage and survivorship bias; separate research from final holdout data.
- No assumed stop loss unless the user explicitly approves it.
- Prefer KRX regular session, unadjusted prices, and verify data source/session rather than assuming.
- Do not claim historical files are present until their bytes and hashes are verified.
