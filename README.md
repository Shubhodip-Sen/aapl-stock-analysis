# AAPL Stock Market Analysis (2020–2025)

Exploratory data analysis of Apple Inc. (AAPL) stock performance over a 5-year period, using Python (pandas, matplotlib) to examine price trends, returns, volatility, and moving averages.

## Overview

This project pulls 5 years of historical AAPL stock data and analyzes it to answer a simple question: how has Apple's stock actually performed, and how volatile has that performance been?

## Data

- **Source:** Yahoo Finance, via the `yfinance` Python library
- **Ticker:** AAPL
- **Period:** January 2020 – December 2024
- **Frequency:** Daily

## Methods

- Daily return calculation (`pct_change()`)
- Daily and annualized volatility (rolling standard deviation)
- 30-day and 100-day simple moving averages
- Monthly return aggregation
- Total return, CAGR, and maximum drawdown calculations

## Key Findings

| Metric | Value |
|---|---|
| Total return (2020–2024) | **244.0%** |
| CAGR | **28.1%** |
| Max drawdown | **-31.4%** |
| Annualized volatility | **31.7%** |
| Best month | Aug 2020 (+21.7%) |
| Worst month | Dec 2022 (-12.2%) |

- AAPL nearly tripled in price over the 5-year window, growing from ~$70 to ~$250.
- Returns are volatile month-to-month, but positive months dominate over the long run.
- The 30-day moving average stayed above the 100-day average for most of the period, consistent with a sustained uptrend; dips below it lined up with broader market corrections (e.g. mid-2022).
- Daily returns cluster tightly around zero with occasional outliers — typical large-cap stock behavior.

## Tools

`Python` · `pandas` · `matplotlib` · `yfinance`

## File

- `Stock_Market_Analysis__(AAPL)_.ipynb` — full notebook with code, charts, and analysis
- `AAPL_2020_2025.csv` — raw price data used in the analysis
