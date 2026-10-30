# quant-equity-strategies

Size & Value Portfolio Construction · Lagged Trend Strategy Backtest

Independent, AI-assisted portfolio research using traceable public historical inputs. Real observations and analyst-created scenarios are labelled separately.

## Projects
- [Size & Value Portfolio Construction](projects/size-value-allocation/README.md) — Quant research · Asset management
- [Lagged Trend Strategy Backtest](projects/trend-backtest/README.md) — Quant research · Performance analysis

## Reproduce
Requires Node.js 22 or later; no third-party packages. Run `node analysis.mjs`. Frozen inputs are included under data/. Calculated outputs are in projects/. Raw source documentation and assumptions are in each project README.

## Data provenance
Kenneth French Data Library: https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html. September 2026 CRSP vintage; monthly rows 200001–202512. Original percentages converted to decimal returns. Only the first value-weighted monthly table is used. Upstream historical revisions mean these are not point-in-time data. Download files: F-F_Research_Data_Factors_CSV.zip and 6_Portfolios_2x3_CSV.zip under https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/ftp/.

Retrieved 2026-10-30. Upstream data remain subject to their source terms; no ownership of source data is claimed.

## Checks
The script checks date alignment, valid observations, risk contribution totals, a standard option-pricing reference value and the projected balance-sheet equation.
