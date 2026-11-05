# Soft Commodity Quantitative Research

A progressive, reproducible research portfolio focused on coffee, with cocoa and sugar extensions. These are independent educational models inspired by public quantitative finance methods, not proprietary firm models or investment advice.

## Research sequence

- [Coffee Futures Risk & Probability Laboratory](./01_coffee_risk_lab/): How well do empirical and normal distributions describe coffee futures returns and tail risk?
- [Coffee Futures Curve & Relative-Value Model](./02_futures_curve_relative_value/): What can futures curves and cross-market spreads reveal about relative pricing?
- [Stochastic Coffee Inventory & Price Simulator](./03_stochastic_inventory_simulator/): How do physical inventory constraints and stochastic shocks affect simulated prices?
- [Machine Learning for Commodity Spreads & Volatility](./04_ml_spread_volatility/): Do machine-learning models improve out-of-sample spread or volatility forecasts?
- [Multi-Commodity Portfolio & Risk Optimization Engine](./05_portfolio_optimization/): How should a soft-commodity portfolio allocate exposure under tail-risk constraints?

## Reproducibility and conventions
- Record each data source, license, download date, contract ticker, unit, roll rule, and observation timestamp.
- Do not commit paid/licensed data, API keys, or confidential material.
- Keep raw inputs immutable and generated outputs reproducible.
- Split time series chronologically; prevent look-ahead bias.
- Evaluate economic assumptions, transaction costs, futures roll mechanics, and out-of-sample stability.
- Label illustrative or synthetic data explicitly.

## Setup
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Open this repository folder in VS Code, select the `.venv` Python interpreter, and begin with Project 01.
