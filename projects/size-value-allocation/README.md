# Size & Value Portfolio Construction

How does a transparent size/value tilt compare with the broad market?

## Role relevance
Quant research · Asset management

## Data
2000–2025 monthly data; evaluation 2010–2025. Source: https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html. Retrieved 2026-10-30.

## Method
Use the six French value-weighted size/book-to-market portfolios. Fixed weights: 5/10/35/5/10/35%, in source column order. Rebalance monthly; cost 10bp per dollar bought or sold, including initial entry. Weights are illustrative design choices, not optimized. Report 2010–2025 separately from 2000–2009 context. Sharpe uses monthly RF; CAGR compounds net returns.

## Findings
The tilt returned 12.30% annualized versus 14.06% for the market. The result demonstrates a style allocation trade-off; it does not establish stock-level selection skill.

- Net CAGR 12.30%
- Sharpe 0.65
- Max drawdown -35.43%

## Interpretation and limits
Research portfolio proxies are not directly tradable securities. Historical data are the September 2026 revised vintage, not a point-in-time archive. No claim of a previously untouched holdout or future alpha. Taxes and intra-portfolio trading costs are excluded.

See [computed results](results.csv). Reproduce with `node analysis.mjs` from the repository root. This is an independent, AI-assisted portfolio case study, not employment experience or a company-issued forecast.
