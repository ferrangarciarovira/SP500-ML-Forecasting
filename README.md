# S&P 500 Forecasting with Machine Learning  

This project explores the predictive power of machine learning models in forecasting returns of the S&P 500 index over short- to medium-term horizons. The framework includes rigorous feature engineering, model training and evaluation, and out-of-sample backtesting. The goal is to assess the viability of ML-based return forecasts in a real-world trading context.

---

## Project Overview

- **Objective**: Identify which ML algorithms (e.g., Ridge, Lasso, XGBoost) offer consistent predictive power on equity index returns.
- **Approach**:
  - Predict log returns of the S&P 500 using daily data.
  - Evaluate forecasts for 1-day, 1-week, and 1-month ahead horizons.
  - Apply rolling-window backtesting to simulate live performance.
  - Analyze economic value through cumulative returns and Sharpe ratios.
- **Scope**: Combines financial signal processing, time-series modeling, and ML performance evaluation in a fully reproducible pipeline.

---

## Models and Techniques

- **Regression Models**: Ridge, Lasso, Decision Tree Regressor, XGBoost
- **Feature Engineering**:
  - Technical indicators (RSI, MACD, moving averages)
  - Lagged returns, volatility, momentum factors
  - Calendar/time features
- **Backtesting**: Expanding and rolling-window forecasts with out-of-sample evaluation

---

## Repository Structure

- `data/`: contains match CSV and Excel files
- `notebooks/`: main analysis notebook
- `reports/`: final presentation (PDF)
- LICENSE
- README.md
- requirements.txt
  
## Tools & Libraries

- `Python 3.10+`
- `pandas`, `numpy`, `scikit-learn`, `xgboost`
- `matplotlib`, `seaborn`, `yfinance`
- `statsmodels` (for comparison with ARIMA/GARCH)

---

Feel free to connect via [LinkedIn](https://www.linkedin.com/in/ferrangarciarovira/) or view more projects on [GitHub](https://github.com/ferrangarciarovira).
