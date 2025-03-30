# Bitcoin-Price-Predictor
This model is useful to find the BTC price of next 10 days. 

# Introduction
The purpose of this project is to build a machine learning model that predicts Bitcoin prices using historical data.

# Requirements
- Python: 3.x
- Libraries: numpy, pandas, matplotlib, keras, sklearn, plotly, mplfinance

# Data set
Dataset was downloaded from the yahoo finance website.
The dataset used contains historical Bitcoin prices with columns such as Date, Open, High, Low, Close prices and volume.

# Model Building
- LSTM Model: The core of the model is an LSTM network, which is great for time-series forecasting.
  LTSM = Long Short Term Memory

- The architecture of the model consists of:
      * Input Layer: LSTM layer with 128 units, which returns sequences.
      * Second LSTM Layer: LSTM layer with 64 units to further learn from the data.
      * Dense Layer: A fully connected layer with 25 units.
      * Output Layer: A single unit output layer that predicts the Bitcoin closing price.

# Model Training
The model is trained using historical data and split into training and testing.
- Training Set: First portion of the data. (90%)
- Test Set: Remaining data for model evaluation. (10%)

# Prediction
The trained model is used to predict the Bitcoin price for the next 10 days.
Predictions are visualized in a line plot showing the future predicted prices.

# Conclusion
The model successfully predicts Bitcoin prices based on historical data and provides a visualization of the predicted future prices.
