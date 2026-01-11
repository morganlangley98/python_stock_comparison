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
| **CSU.TO** | 0.1222 | $2401 | YYYY-MM-DD |
| **ZETA** | 0.1101 | $19.10 | YYYY-MM-DD |
| **MDB** | 0.1042 | $230.04 | YYYY-MM-DD |
| **OKTA** | 0.0942 | $88.72 | YYYY-MM-DD |
| **FOUR** | 0.0683 | $64.46 | YYYY-MM-DD |
| **UNH** | 0.1171 | $263.73 | YYYY-MM-DD |
| **DEO** | 0.0753 | $114.84 | YYYY-MM-DD |
| **VHI.TO** | 0.0670 | $6.43 | YYYY-MM-DD |
| **PYPL** | 0.0864 | $66.9 | YYYY-MM-DD |
| **MELI** | 0.0742 | $2206 | YYYY-MM-DD |
| **BN** | 0.0811 | $47.41 | YYYY-MM-DD |