# AR–GARCH VaR Backtesting

## Description
This project implements Value-at-Risk (VaR) estimation using an
AR(1)–GARCH(1,1) model on financial return data and evaluates model
performance using regulatory backtests.

## Methodology
- Augmented Dickey–Fuller test for stationarity
- ARMA model selection using AIC
- Residual diagnostics (Ljung–Box)
- ARCH LM test for volatility clustering
- AR–GARCH volatility modeling
- One-step-ahead VaR estimation
- Kupiec unconditional coverage test
- Christoffersen independence test

## Results
- Returns are stationary
- Volatility clustering is present
- VaR coverage is conservative
- Violations exhibit clustering

## Tools
Python, NumPy, Pandas, statsmodels, arch