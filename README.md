# Portfolio Returns Tear Sheet

A script to generate performance metrics for a specific stock against a benchmark using `pyfolio`, handling timezone mismatches (e.g. LSE vs NYSE) automatically.

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