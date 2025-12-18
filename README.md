# SMA-Crossover-Trading-Strategy
A Python-based backtesting engine for Moving Average Crossover strategies using Pandas and yfinance.
# Algorithmic Trading: SMA Crossover Strategy

## Project Overview
This project backtests a technical trading strategy on Apple (AAPL) stock data from 2024-2025. It identifies buy/sell signals based on the intersection of the 20-day and 50-day Simple Moving Averages (SMA).

## Key Features
* **Data Source:** Real-time financial data via Yahoo Finance API (`yfinance`).
* **Bias Correction:** Implements a T+1 lag on trading signals to eliminate look-ahead bias.
* **Visualization:** Uses Matplotlib to plot entry/exit points against price action.

## Technologies Used
* Python
* Pandas (Data Manipulation)
* NumPy (Vectorized Logic)
* Matplotlib (Visualization)
