# 📈 Stock Market Price Prediction Using ARIMA in R

This project uses **R programming** to forecast stock prices using the **ARIMA (AutoRegressive Integrated Moving Average)** time series model.  
It was developed and executed on **Google Colab** with R support.

---

## 🧠 Project Overview

The goal of this project is to:
- Collect **real-time stock data** from Yahoo Finance using the `quantmod` package.
- Analyze and visualize historical closing prices.
- Build and train an **ARIMA model** for forecasting.
- Evaluate model accuracy using metrics like RMSE, MAE, and MAPE.
- Predict and visualize the **next 30 days** of stock prices.

---

## 🧩 Technologies Used
- **R Programming**
- **Google Colab**
- **quantmod** – Fetching stock data from Yahoo Finance  
- **forecast** – ARIMA modeling and forecasting  
- **ggplot2** – Data visualization  
- **tseries** – Stationarity and statistical testing  
- **dplyr** – Data manipulation

---

## 📊 Example Results

**Model Accuracy (Example for AAPL):**
| Metric | Training Set | Test Set |
|---------|---------------|----------|
| RMSE | 2.69 | 29.29 |
| MAE | 1.99 | 22.32 |
| MAPE | 1.44% | 10.51% |

**Interpretation:**
The ARIMA model achieved good accuracy on training data and reasonable performance on test data, considering the high volatility of stock markets.

---

## ⚙️ How to Run This Project

1. Open **Google Colab**
2. Change runtime to **R**  
   *(Runtime → Change runtime type → R)*
3. Install required libraries:
   ```r
   install.packages(c("quantmod", "forecast", "tseries", "ggplot2", "dplyr"))
