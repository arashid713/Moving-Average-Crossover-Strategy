# Moving-Average-Crossover-Strategy
This project implements a basic Moving Average Crossover trading strategy using historical stock data. The strategy involves using two moving averages: a short-term moving average (SMA) and a long-term moving average. The strategy generates buy and sell signals based on the crossover of these moving averages.

Features

Fetch historical stock data using yfinance
Calculate short-term and long-term moving averages
Generate buy and sell signals based on moving average crossovers
Backtest the strategy to evaluate performance

Usage

Fetch Historical Data:
Specify the stock ticker, start date, and end date.
Use yfinance to download the data.
Calculate Moving Averages:

Define the short-term and long-term windows.
Calculate the moving averages for the closing prices.
Generate Signals:

Create buy signals when the short-term moving average crosses above the long-term moving average.
Create sell signals when the short-term moving average crosses below the long-term moving average.
Backtest the Strategy:

Simulate trading based on the generated signals.
Calculate the portfolio value over time starting with an initial capital.
