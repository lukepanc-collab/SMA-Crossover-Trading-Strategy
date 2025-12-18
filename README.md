# SMA Crossover Algorithmic Trading Bot

A Python-based backtesting engine for Moving Average Crossover strategies using Pandas and yfinance.

![Strategy Visualization](SMA-Crossover-Strategy-Chart.png)
*(Note: Replace 'chart_image.png' with the actual filename of your chart screenshot)*

## 📈 Project Overview
This project backtests a technical trading strategy on Apple (AAPL) stock data from 2024-2025. It algorithmically identifies buy/sell signals based on the intersection of the 20-day and 50-day Simple Moving Averages (SMA).

## ✨ Key Features
* **Automated Data Retrieval:** Fetches real-time financial data via the Yahoo Finance API (`yfinance`).
* **Bias Correction:** Implements a **T+1 lag** on trading signals to eliminate look-ahead bias, ensuring realistic backtest results.
* **Vectorized Logic:** Uses NumPy for high-speed signal generation instead of slow iteration.
* **Visualization:** Generates actionable charts with Matplotlib plotting entry/exit points against price action.

## 🛠️ Technologies Used
* **Python**
* **Pandas** (Data Manipulation & Time-series analysis)
* **NumPy** (Conditional Logic)
* **Matplotlib** (Data Visualization)
* **yfinance** (API Wrapper)

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install yfinance pandas matplotlib numpy
