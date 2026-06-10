# 📈 Time Series Forecasting & Portfolio Optimization Using Statistical Models

\

\

## 🚀 Overview

This project was developed as part of the **Time Series Analysis 2026 Capstone Project** at **IIT Guwahati**.

The project focuses on applying statistical time-series forecasting techniques to predict stock prices, analyze market volatility, optimize portfolio allocation, and validate predictions through live virtual trading using the StockGro platform.

### 🎯 Key Objectives

✅ Forecast future stock prices using multiple time-series models

✅ Compare model performance using RMSE, MAPE, and Directional Accuracy

✅ Analyze volatility, trends, and stock correlations

✅ Construct a diversified ₹10,00,000 investment portfolio

✅ Validate forecasts against real market outcomes

✅ Evaluate portfolio performance through virtual trading

---

## 📊 Dataset

**Source:** Yahoo Finance (yFinance API)

**Period:** January 2021 – January 2026

**Frequency:** Daily Closing Prices

### 🏢 Selected Stocks

| Stock         | Sector                 |
| ------------- | ---------------------- |
| 🏦 HDFCBANK   | Banking                |
| 💻 INFY       | Information Technology |
| 💊 SUNPHARMA  | Pharmaceuticals        |
| 🛒 HINDUNILVR | FMCG                   |
| 🚗 M&M        | Automobile             |
| ⚡ RELIANCE    | Energy                 |
| 📡 BHARTIARTL | Telecom                |

---

## 🛠️ Methodology

### 📥 Data Collection

* Historical NSE stock data using yFinance
* Daily closing prices from 2021–2026

### 🧹 Data Preprocessing

* Missing value handling
* Stationarity testing (ADF Test)
* First-order differencing
* Train-test split

### 🤖 Forecasting Models

| Model           | Purpose                         |
| --------------- | ------------------------------- |
| 📉 ARIMA        | Statistical forecasting         |
| 🔮 Prophet      | Trend & seasonality forecasting |
| 📈 Holt-Winters | Exponential smoothing           |

### 📏 Evaluation Metrics

* 📊 RMSE
* 📉 MAPE
* 🎯 Directional Accuracy

---

## 📈 Volatility & Trend Analysis

Performed:

* 📊 Rolling Volatility Analysis
* 📉 Risk-Return Analysis
* 🔗 Correlation Analysis
* 📈 Long-Term Growth Analysis
* 🧩 Trend Decomposition

### 🔍 Key Findings

🏆 M&M delivered the highest 5-year growth (423.83%)

📡 Bharti Airtel showed strong sector momentum

🛒 HINDUNILVR exhibited the lowest volatility

🔗 Diversification opportunities were identified through low stock correlations

---

## 💰 Portfolio Construction

### 🎯 Forecast-Guided Allocation

Higher expected returns → Higher allocation

### ⚖️ Volatility-Aware Allocation

Lower volatility → Higher weight

### 🛡️ Diversification Strategy

Multi-sector exposure to reduce risk

### 💵 Initial Capital

**₹10,00,000**

🏆 Highest Allocation: HDFC Bank (22.46%)

⚠️ Lowest Allocation: M&M (0.03%)

---

## 🏆 Model Comparison

| Model           | Strength                    |
| --------------- | --------------------------- |
| 📉 ARIMA        | Statistical forecasting     |
| 🔮 Prophet      | Stable trend prediction     |
| 📈 Holt-Winters | Portfolio-level forecasting |

### ✅ Final Model Selected

**Holt-Winters Exponential Smoothing**

Reason:

* Stable forecasts
* Consistent performance
* Better portfolio-level decision making

---

## 📋 Virtual Trading Results

### 💹 Portfolio Performance

| Metric                | Value      |
| --------------------- | ---------- |
| Initial Investment    | ₹9,98,437  |
| Final Portfolio Value | ₹10,05,058 |
| Net Return            | 🟢 +0.56%  |

### 🌟 Top Contributors

✅ Bharti Airtel

✅ HDFC Bank

✅ Sun Pharma

### ⚠️ Underperformer

❌ Infosys

---

## 🔍 Predicted vs Actual Outcomes

Key observations from live market execution:

✅ Stable stocks showed better forecast accuracy

⚠️ Volatile stocks exhibited larger prediction errors

🚀 Bharti Airtel significantly outperformed expectations

🛡️ Diversification helped offset losses from individual stocks

---

## 🔮 Future Improvements

* 🧠 LSTM Networks
* 🤖 GRU Models
* 🚀 Transformer-Based Forecasting
* 📊 Interactive Dashboard
* ⚡ Real-Time Market Monitoring

---

## 💻 Tech Stack

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📉 Matplotlib
* 🎨 Seaborn
* 📈 Statsmodels
* 🔮 Prophet
* 🤖 Scikit-Learn

---

## 📂 Repository Structure

```text
TSA-Capstone-Project/
│
├── 📓 TSA_Capstone_Full.ipynb
├── 📄 Capstone_Report_NeelKapadi.pdf
├── 📘 README.md
└── 📁 images/
```

---

## 👨‍💻 Author

**Neel M. Kapadi**

🎓 M.Tech, IIT Guwahati

📈 Time Series Analysis Capstone Project 2026
