# Gold-Price-Prediction-Using-Time-Series-Forecasting-and-Machine-Learning-Techniques
Gold price prediction using time series and machine learning techniques. The project uses Yahoo Finance data (2010–2024) and applies preprocessing, feature engineering, and models like ARIMA, SARIMA, and Random Forest. Results show SARIMA performs best, capturing trend and seasonality effectively for accurate forecasting.

# 📈 Gold Price Prediction using Time Series & Machine Learning

## 📌 Overview

This project focuses on predicting gold prices using historical data and machine learning techniques. Gold is considered a safe investment asset, especially during economic uncertainty. Accurate forecasting helps investors and financial institutions make better decisions and manage risk effectively.

---

## 🎯 Objectives

* Analyze historical gold price trends
* Perform data preprocessing and feature engineering
* Build time series forecasting models
* Compare model performance using evaluation metrics
* Generate insights for financial decision-making

---

## 📊 Dataset

* **Source:** Yahoo Finance (GC=F)
* **Time Period:** 2010 – 2024
* **Frequency:** Daily data
* **Target Variable:** Closing Price

### Features:

* Date
* Open
* High
* Low
* Close (Target)
* Volume

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Handled missing values using forward fill
* Smoothed data using 7-day rolling average
* Removed outliers using IQR method
* Tested stationarity using ADF test

### 2. Feature Engineering

* Lag features (1-day, 7-day, 30-day)
* Rolling mean and standard deviation
* Daily returns
* Time-based features (month, day)
* Data normalization using MinMaxScaler

### 3. Models Used

* **ARIMA** – Basic time series model
* **SARIMA** – Captures seasonality
* **Random Forest** – Machine learning approach

---

## 📏 Evaluation Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)

---

## 📈 Results

* **SARIMA** achieved the best performance
* **Random Forest** showed moderate accuracy
* **ARIMA** had higher prediction errors

SARIMA effectively captured both trend and seasonal patterns in gold prices.

---

## 💡 Key Insights

* Seasonality plays a major role in gold price prediction
* Feature engineering improves model performance
* Data smoothing helps reduce noise and improve accuracy

---

## ⚠️ Challenges

* High volatility in financial data
* Handling non-stationary patterns
* Difficulty in predicting sudden market changes

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Statsmodels
* Matplotlib, Seaborn

---

## 🚀 Future Improvements

* Use deep learning models (LSTM, GRU)
* Include economic indicators (inflation, currency rates)
* Build hybrid models for better accuracy
* Implement real-time prediction system

---

## 📚 References

* Yahoo Finance – Gold Futures Data
* Research papers on LSTM & GRU for price prediction

---
