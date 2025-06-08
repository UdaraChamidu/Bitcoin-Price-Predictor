# Bitcoin Price Predictor 🚀

Predict Bitcoin prices for the next 10 days using historical data and a deep learning LSTM model.

---

## 📖 Overview

This project leverages **15 years of Bitcoin historical price data** from Yahoo Finance to train a deep learning model that forecasts future Bitcoin closing prices. It uses a **Long Short Term Memory (LSTM)** neural network, a specialized architecture for analyzing sequential time series data, to capture trends and dependencies in Bitcoin price movements.

---

## ⚙️ Features

- **Automatic data download** from Yahoo Finance (`BTC-USD` pair).
- Data preprocessing including scaling and moving average calculations.
- **LSTM-based deep learning model** designed for time-series forecasting.
- Visualization of:
  - Historical closing prices
  - Moving averages (100-day & 365-day)
  - Actual vs predicted prices on test data
  - Predicted prices for the upcoming 10 days.
- Split data into training (90%) and testing (10%) sets for model validation.

---

## 🧠 Why LSTM?

LSTM (Long Short Term Memory) networks are powerful recurrent neural networks designed to:

- **Remember long-term dependencies** in sequences, which is crucial for time series data.
- **Handle the vanishing gradient problem** in traditional RNNs.
- Effectively learn temporal patterns in Bitcoin price fluctuations for better predictions.

This makes LSTM ideal for predicting prices based on past sequences of daily closing prices.

---

## 🎯 Results & Conclusion

- The model effectively captures Bitcoin price trends using historical data.
- Predictions align closely with actual prices, demonstrating the power of LSTM for time-series forecasting.
- Useful for traders, analysts, and enthusiasts interested in BTC price forecasting.

---

## 📦 Requirements

- Python 3.7+
- Libraries:
  - `yfinance`
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow` (for Keras)

Install all dependencies with:

```bash
pip install yfinance numpy pandas matplotlib scikit-learn tensorflow


