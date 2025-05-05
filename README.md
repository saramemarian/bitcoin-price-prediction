
# 📊 Bitcoin Price Prediction using Machine Learning

## Overview
This project focuses on predicting Bitcoin prices using historical daily price data and basic machine learning techniques. It serves as an introduction to time series forecasting and financial modeling using Python and pandas.

## 📁 Dataset
- Source: [CryptoDataDownload.com](https://www.cryptodatadownload.com/)
- File used: `HitBTC_BTCUSD_d.csv`
- Columns:
  - `Date`, `Open`, `High`, `Low`, `Close`, `Volume BTC`, `Volume USD`

## 🧹 Preprocessing Steps
- Removed unnecessary header rows
- Parsed the `Date` column to datetime
- Extracted `Year`, `Month`, and `Day` from date
- Dropped irrelevant columns like `Symbol` and `Unix Timestamp`

## 📈 Model Used
- **Linear Regression**
- Target: `Close` price
- Features: `Open`, `High`, `Low`, `Volume BTC`, `Volume USD`, `Year`, `Month`, `Day`

## 🧪 Evaluation
- Metric: **Mean Squared Error (MSE)**
- Result: `52,809.81`

## 🔧 Tools & Libraries
- Python
- pandas
- scikit-learn
- Google Colab

## 📌 Notes
- The model is basic and only serves as a starting point.
- Further work may include: advanced models (e.g., LSTM, XGBoost), hyperparameter tuning, feature engineering, and cross-validation.
