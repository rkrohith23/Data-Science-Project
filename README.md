# Data-Science-Project
Data Science Project - 7PAM2002-0509-2024
Forecasting Gold Prices Using Machine Learning and LSTM Models

This project applies Machine Learning (ML) and Deep Learning (DL) techniques to forecast daily gold prices using multivariate time series data (SPX, USO, SLV, EUR/USD).

📌 Key Highlights

Preprocessing: scaling, lag-based features, exploratory analysis

Models: Linear Regression, Lasso Regression, Random Forest, XGBoost and LSTM

Evaluation: RMSE, MAE, R², MAPE with residual and forecast plots

Forecasting: 24-month (LSTM) and 60-month (RF/XGBoost) recursive predictions

🔍 Findings

Linear & Lasso underperformed (R² < 0)

Random Forest & XGBoost achieved best accuracy (R² ≈ 0.95)

LSTM captured sequential dependencies (R² ≈ 0.88) and produced stable long-term forecasts

📂 Report

The detailed analysis and discussion are available in the Final Project Report.
