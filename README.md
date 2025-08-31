# Data Science Portfolio — Economics, Finance & Business Intelligence
_By Ricardo Ruiz_

A curated set of reproducible Jupyter notebooks showcasing applied **time-series forecasting**, **econometrics**, and **machine learning** for **economics, finance, and BI** use cases. The goal: demonstrate end-to-end analytical thinking — from data acquisition and EDA, through rigorous modeling and validation, to business-ready interpretation and visualization.

> Tech stack: Python · pandas · numpy · statsmodels (ARIMA/SARIMA/SARIMAX, VAR/VARMAX) · scikit-learn · pmdarima · yfinance · matplotlib · seaborn · arch (GARCH)

---

## What’s inside
- **Forecasting & Econometrics**
  - ARIMA/SARIMA/SARIMAX with AIC/BIC model selection, ADF stationarity tests, seasonal decomposition, ACF/PACF analysis
  - Exogenous drivers via ARIMAX/SARIMAX; causality checks (Granger), VAR/VARMAX for multivariate dynamics
  - Volatility modeling with **ARCH/GARCH** for risk-aware forecasts
- **Machine Learning for Business**
  - Feature engineering for demand forecasting, inventory optimization, pricing, and KPI tracking
  - Baselines vs. advanced ML (e.g., tree-based models, deep learning) with clear, comparable metrics
- **Communication**
  - Clean plots, interpretable diagnostics, and business-focused takeaways
  - Reproducible code and documented assumptions

---

## Highlighted notebook
**Apple Stock Price Forecast using SARIMAX (June 7, 2023 → July 31, 2025)**  
A long-horizon SARIMAX forecast of AAPL that later matched reality with **1.74% relative error** at the 25-month mark.  
Includes:
- Train/test backtesting (80/20), MSE comparison across ARIMA/SARIMA/ARIMAX/SARIMAX
- Granger causality (MSFT, NVDA), seasonality diagnostics, and volatility via GARCH
- Discussion of when statistical baselines outperform or complement ML in production

> Educational content — **not investment advice**.

---

## Why this portfolio
- **Rigor + practicality**: econometric foundations paired with production-minded evaluation
- **Explainability**: models that decision-makers can trust and challenge
- **Transferable patterns**: the same techniques power demand planning, budgeting, capacity, and risk analytics

---

## Getting started
```bash
# Clone
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# (Option A) Create environment from requirements
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# (Option B) Conda
conda env create -f environment.yml
conda activate ds-eco-fin-bi
