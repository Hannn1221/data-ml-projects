# Macroeconomic & Data Science Modeling Pipeline  
*Data + ML Portfolio — Econometrics Meets Machine Learning*

## Overview  
This project builds a full macro-forecasting pipeline combining econometrics and machine learning. It automates data loading, stationarity testing, feature engineering, model estimation, and forecast comparison across OLS, ARIMA, and XGBoost.

## What I Did  
- Pulled macroeconomic time series from FRED and OECD.  
- Applied ADF, PP, and KPSS stationarity tests.  
- Built lag features and transformed non-stationary data.  
- Estimated OLS, ARIMA, and XGBoost models.  
- Compared out-of-sample forecast accuracy.

## How I Did It  
All processes were scripted in Python (`statsmodels`, `pandas`, and `xgboost`). Diagnostics were used to validate residual behaviour, and forecasts were evaluated with MAPE and RMSE.

## Why It Matters  
Macro forecasting requires combining theory-driven models with ML flexibility. This pipeline shows how an analyst builds scalable forecasting systems.

---

## Figures  
![Figure 1: Stationarity Diagnostic Outputs](figures/macro_fig1.png)  
![Figure 2: Forecast Comparison (ARIMA vs ML)](figures/macro_fig2.png)

---

## Code Reference  
`src/data_science_and_macroeconomic_modeling.py`
