# Lagged Trend Strategy Backtest

Can a simple trend rule change the market drawdown profile?

## Role relevance
Quant research · Performance analysis

## Data
2000–2025 monthly data; evaluation 2010–2025. Source: https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html. Retrieved 2026-10-30.

## Method
At each month start, hold the market if its previous 12 completed monthly total returns compound above zero; otherwise hold the RF proxy. Signals exclude the current month. Charge 10bp per full allocation switch. Compare against buy-and-hold for 2010–2025; also report 2000–2009 context in the CSV. No parameter search.

## Findings
Trend CAGR was 10.54%, with maximum drawdown -20.77%; market CAGR was 14.06% and drawdown -24.84%.

- CAGR 10.54%
- Max drawdown -20.77%
- Sharpe 0.73

## Interpretation and limits
Monthly execution assumes the signal can be implemented at the period boundary. Real execution delay, instrument tracking error and taxes are excluded. The market index is a research proxy. Historical evaluation is not a live or pristine holdout track record.

See [computed results](results.csv). Reproduce with `node analysis.mjs` from the repository root. This is an independent, AI-assisted portfolio case study, not employment experience or a company-issued forecast.
