# 📈 Stock Price Forecasting using Machine Learning

## Overview

This project aims to predict the next day's stock closing price using Machine Learning techniques. Historical stock market data was obtained using the Yahoo Finance API and analyzed using Python.

The project compares multiple machine learning models and evaluates their performance using standard regression metrics.

---

## Dataset

* Source: Yahoo Finance
* Stock Used: Apple (AAPL)
* Time Period: 2020 - 2025

Features Used:

* Open
* High
* Low
* Close
* Volume

Target Variable:

* Tomorrow_Close (Next Day Closing Price)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Yahoo Finance (yfinance)

---

## Exploratory Data Analysis

The dataset was analyzed to understand stock price trends and identify patterns.

Visualizations include:

* Historical stock price trends
* Actual vs Predicted stock prices

---

## Models Implemented

### 1. Linear Regression

A regression model used to predict the next day's closing stock price based on current market features.

### 2. Random Forest Regressor

An ensemble learning model that combines multiple decision trees to improve prediction performance.

---

## Results

### Linear Regression

| Metric   | Value  |
| -------- | ------ |
| MAE      | 2.00   |
| RMSE     | 2.75   |
| R² Score | 0.9957 |

### Random Forest

| Metric   | Value  |
| -------- | ------ |
| MAE      | 1.01   |
| RMSE     | 1.39   |
| R² Score | 0.9989 |

---

## Project Structure

```text
stock-price-forecasting-ml/
│
├── stock_price_forecasting.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Future Improvements

* LSTM-based Deep Learning Model
* Time Series Forecasting
* Technical Indicators (Moving Averages, RSI)
* Streamlit Web Application
* Real-time Stock Prediction Dashboard

---

## Key Learnings

* Data preprocessing and feature engineering
* Regression modeling
* Model evaluation using MAE, RMSE, and R²
* Stock market forecasting fundamentals

---

## Author

Lakshaya L
B.Tech / IIT BS Student
Aspiring Data Scientist & AI Engineer
