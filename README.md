# LSTM neural network for stock price prediction

## Overview

This project applies a two-layer LSTM to daily closing price data to predict the next day's price, using a 60-day lookback window, and evaluates its predictive performance using RMSE and cross validation

## Features

Uses Yfinance API to collect historical stock data

Normalised data using MinMaxScaler and implemented an 80/20 train test split

Used Tensorflows Keras for LSTM neural network, with two LSTM layers followed by dense layers

Calculated RMSE as the performance metric

Visualised side-by-side data of actual price against predicted price using Matplotlib

## Results

trained on AAPL daily closing price data from 2017 - 2024

Acheived an RMSE or $5.41 (approximately 3.1% of asset price)

predicted values track the actual stock price closely

## Limitations

trained only on a single ticker and a single train test split

Model architecture parameters (60-day window, 50 LSTM units, 10 epochs) were not systematically tuned

## Tech stack

Python, Tensorflow, Keras, NumPy, Pandas, Matplotlib, Yfinance, Sci-kit learn
