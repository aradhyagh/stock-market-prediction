# Stock Price Forecasting App

This is a Streamlit-based web application for **stock price forecasting** using an LSTM deep learning model.  
It allows you to:
- Load fresh stock data from Yahoo Finance
- Visualize the past 30 days of stock prices
- Predict the next _n_ days of stock prices using a pre-trained model and scaler

---

url: https://stock-market-prediction-97haqczwb4xyqjd9usd55j.streamlit.app/

---

## ✅ Features

- ✅ Input any stock ticker symbol (e.g., `RELIANCE.NS`, `AAPL`, `GOOGL`)
- ✅ Select historical data period: 1 year, 5 years, or 10 years
- ✅ Interactive visualization of past 30 days stock prices
- ✅ Predict and display future stock prices for user-specified number of days (up to 30)
- ✅ Interactive line chart showing both past prices and future predictions

---

## Installation

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>

2. Install dependencies:
   pip install -r requirements.txt

3. Dependencies
- streamlit
- yfinance
- pandas
- matplotlib
- tensorflow
- scikit-learn
