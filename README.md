# Final_Research_Project

# 📈 Forecasting Inflation in Nigeria Using Machine Learning

This project applies **machine learning** techniques to forecast inflation in Nigeria using key economic indicators such as:

- Consumer Price Index (CPI)
- Money Supply
- Exchange Rate
- Monetary Policy Rate
- Currency in Circulation
- And more

Both **linear** and **non-linear** models were compared to provide insights that support **economic planning and investment decisions**.

🎯 Objectives

- Build dataset from **CBN** and **NBS** sources
- Preprocess and engineer features (e.g., **lags**, **rolling averages**)
- Train and evaluate multiple models:
  - Linear: **Ridge, Lasso, Elastic Net**
  - Non-linear: **Random Forest, XGBoost, SVR**
  - Time series: **ARIMA, VAR**
- Compare performance using **R², RMSE, MAE**
- Identify **key indicators** driving inflation

📊 Results Summary

- **Ridge Regression** → Best linear model
- **SVR (Polynomial Kernel)** → Best non-linear model
- **ARIMA & VAR** → Underperformed compared to ML models
- **Exchange Rate** and **Money Supply** were found to be strong drivers of inflation

📂 Repository Structure

Final_Research_Project/
data/
notebooks/
results/  
 README.md
