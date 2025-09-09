# LSTM neural network for stock price prediction

## overview
this project applies an LSTM neural network to time-series data for stock prediction and evaluates its predictive performance using RMSE and cross validation

## features
- uses Yfinance API to collect historical stock data
- normalised data using MinMaxScaler and implemented an 80/20 train test split
- used Tensorflows Keras for LSTM neural network
- claculated RMSE as the performance metric
- visualised side-by-side data of actual price against predicted price using Matplotlib

## results
- trained on stock data from 2017 - 2024
- acheived an RMSE or $5.41 (3.1% of asset price)
- predicted values track the actual stock price closely

## tech stack
- Python, Tensorflow, Keras, NumPy, Pandas, Matplotlib, Yfinance, Sci-kit learn
