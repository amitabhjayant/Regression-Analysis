# Regression-Analysis
Developed and estimated 7 progressive econometric models (OLS with HAC correction, log-log, first-difference, and interaction specifications) to analyze monthly UPI transaction behavior using Python (statsmodels, pandas, numpy).
Identified that the relationship between cash and UPI flips from negative substitution in levels to positive co-movement in short-run growth models, demonstrating the importance of detrending and model specification in time-series analysis.
Quantified that a 1% increase in cash growth is associated with ~0.53% increase in UPI growth, and a 1% increase in card growth raises UPI growth by ~0.27%, revealing digital ecosystem complementarity rather than pure substitution.
Incorporated macroeconomic proxies (IIP for income), liquidity channels (cash circulation), digital depth (card transactions), inflation, seasonal month dummies, and a COVID-19 interaction term, achieving final model R² = 0.916.
Diagnosed and corrected for autocorrelation (Durbin-Watson improved from 1.13 to 2.08), and omitted variable bias, providing policy-relevant insights on payment system resilience and transaction demand.
