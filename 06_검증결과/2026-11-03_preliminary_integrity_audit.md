# 2026-11-03 CSV preliminary integrity audit

Scope: Three ChatGPT Library CSVs whose original bytes were materialized and SHA-256 checked. This is not a complete audit of all historical uploads.

## Original files
| filename | bytes | SHA-256 | rows | date range | duplicate dates | OHLC missing | OHLC logical errors |
|---|---:|---|---:|---|---:|---:|---:|
| 035250(6).csv | 47249 | e4e6a7c756ac6eb354ce043c87a04c9a0cfaf85babfb00d0e61a130bf8b05a64 | 600 | 2024-05-07 to 2026-10-26 | 0 | 0 | 0 |
| 093370(7).csv | 45108 | 05e003f32ffce11b316ac331907e4d080ba47cfbbc2ecc9ec42e3654576c1232 | 600 | 2024-05-07 to 2026-10-26 | 0 | 0 | 0 |

## Search history
- Filename: 검색전체이력.csv
- Bytes: 1183696
- SHA-256: 5fe76b38cd0c4e0ea6f0e3ca7648ce6c6d63f49ae76478ac6c8d8510ae05f0e4
- Rows: 4854, columns: 20, unique codes: 652
- D0 range: 2025-12-30 to 2026-10-21
- Formula counts: ATR8_VOL3=2431, 빈도형=1636, 정밀형=787
- Exact duplicate rows: 0
- Duplicate composite keys (code,D0,formula): 0
- Missing loc: 1 row

## Important limitations
- Original CSV bytes have **not** yet been uploaded to GitHub; this file is an audit record only.
- The source exchange, session, adjustment status, corporate actions, and price accuracy have not been independently validated.
- Historical search records are **not** confirmed ON/TP5 executed trades.
- No net-return, hit-rate, MFE/MAE, or execution-cost performance claims are made here.
- No source files were modified or deleted.
