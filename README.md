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

---

# 📊 Results & Visualizations

### 📈 Multi-Stock Price Comparison

Comparison of historical stock price movements across all selected sectors from 2021–2026.

<img width="1320" height="706" alt="Multi-stock price comparison" src="https://github.com/user-attachments/assets/4aacadb8-0deb-4e81-9fc5-d93594bd2dbe" />

---

### 🥧 Portfolio Allocation

Final capital allocation based on forecasting results, volatility analysis, and diversification strategy.

<img width="837" height="814" alt="Portfolio Allocation Pie Chart" src="https://github.com/user-attachments/assets/4734c71c-a597-47e4-9eeb-14c2b0b71309" />

---

### 🔥 Correlation Heatmap

Correlation analysis used to identify diversification opportunities and reduce portfolio concentration risk.

<img width="855" height="781" alt="Correlation heatmap" src="https://github.com/user-attachments/assets/0454476d-2a0c-4297-9ff7-5b3397d3ee73" />

---

### ⚖️ Risk vs Return Analysis

Risk-return tradeoff analysis showing annualized returns against volatility for selected stocks.

<img width="871" height="626" alt="Risk vs Return plot" src="https://github.com/user-attachments/assets/540791cf-9ff3-4b8d-ba3c-6e8d1ba251d4" />

---

### 📊 20-Day Rolling Volatility

Rolling volatility analysis used to assess changing market risk over time.

<img width="1169" height="549" alt="20 day rolling volatility" src="https://github.com/user-attachments/assets/ab782690-7228-4105-ba1c-2f88db45af7b" />

---

### 🧩 Seasonal Decomposition

Time series decomposition into trend, seasonal, and residual components.

<img width="1322" height="953" alt="seasonal decomposition" src="https://github.com/user-attachments/assets/2bf02421-9844-4aa8-ab1b-4cc91c214db6" />

---

### 📉 ARIMA Forecast

Future stock price forecasting using the ARIMA model.

<img width="1165" height="549" alt="ARIMA forecast" src="https://github.com/user-attachments/assets/ff2d3708-f241-48ea-8389-63f68badfe1d" />

---

### 📈 Holt-Winters Forecast

Forecasting using exponential smoothing techniques.

<img width="1165" height="549" alt="Holts-winter forecast" src="https://github.com/user-attachments/assets/35625274-1ee3-4020-b98e-081235341acb" />

---

### 🔮 Prophet Forecast

Forecasting future trends and uncertainty intervals using Meta Prophet.

<img width="988" height="614" alt="Prophet forecast" src="https://github.com/user-attachments/assets/b603569c-129d-4b12-9887-693ad34475eb" />

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
