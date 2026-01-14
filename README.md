# Portfolio Returns Tear Sheet

'single_stock' notebook to generate performance metrics for a specific stock against a benchmark using `pyfolio`, handling timezone mismatches (e.g. LSE vs NYSE) automatically.

'portfolio_level' to consider portfolio as a whole.


## Setup (using uv)

```bash
uv venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
uv pip install yfinance pyfolio-reloaded jupyterlab ipykernel

```

## Analysis

- Open 'main' notebook
- Update stock ticker for stock of interest and benchmark (match yahoo finance ticker)
- Run analysis


### Current Portfolio and Weightings (Jan 2026)

| Ticker | Weight | Average Price ($) | Date Purchased |
| :--- | :--- | :--- | :--- |
| **CSU.TO** | 0.1332 | $2401 | 2026-01-09 |
| **ZETA** | 0.1195 | $19.10 | 2025-09-08 |
| **MDB** | 0.1183 | $230.04 | 2025-08-15 |
| **OKTA** | 0.1083 | $88.72 | 2025-08-28 |
| **FOUR** | 0.0754 | $64.46 | 2026-01-07 |
| **DEO** | 0.0863 | $114.84 | 2025-02-13 |
| **VHI.TO** | 0.075 | $6.43 | 2026-01-09 |
| **PYPL** | 0.0955 | $66.9 | 2025-09-08 |
| **MELI** | 0.0796 | $2206 | 2025-11-15 |
| **BN** | 0.1089 | $47.41 | 2026-01-08 |