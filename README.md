# 📈 Forecasting Inflation in Nigeria Using Machine Learning

This project applies **machine learning** techniques to forecast inflation in Nigeria using key economic indicators such as:

- Consumer Price Index (CPI)
- Money Supply
- Exchange Rate
- Monetary Policy Rate
- Currency in Circulation
- And more

Both **linear** and **non-linear** models were compared to provide insights that support **economic planning and investment decisions**.

## 🎯 Objectives

- Build dataset from **CBN** and **NBS** sources
- Preprocess and engineer features (e.g., **lags**, **rolling averages**)
- Train and evaluate multiple models:
  - Linear: **Ridge, Lasso, Elastic Net**
  - Non-linear: **Random Forest, XGBoost, SVR**
  - Time series: **ARIMA, VAR**
- Compare performance using **R², RMSE, MAE**
- Identify **key indicators** driving inflation

## 📊 Results Summary

- **Ridge Regression** → Best linear model
- **SVR (Polynomial Kernel)** → Best non-linear model
- **ARIMA & VAR** → Underperformed compared to ML models
- **Exchange Rate** and **Money Supply** were found to be strong drivers of inflation

## 📂 Repository Structure

-Datasets ( Excel )

- Output Plot
- Python File (in .ipynb)
- README.md
- requirements.txt

## ⚙️ How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/Sunday-Ogunya/Final_Research_Project.git
   cd Final_Research_Project

   ```

2. **Set up virtual environment (recommended)**
   python -m venv venv
   source venv/bin/activate # On Mac/Linux
   venv\Scripts\activate # On Windows

3. **pip install -r requirements.txt**
   pip install -r requirements.txt

4. **Launch Jupyter Notebook**
   jupyter notebook

## 📦 Requirements

    The project dependencies are listed in requirements.txt:

- _pandas_
- _numpy_
- _matplotlib_
- _seaborn_
- _scikit-learn_
- _statsmodels_
- _jupyter_

👨‍🎓 Author

Sunday Adeoye Ogunya
MSc Data Science – University of Hertfordshire

🔗 GitHub Repository - *https://github.com/Sunday-Ogunya/Final_Research_Project*
