# Practical-Investing-Fundamentals
Coursework from the university module Practical Investing Fundamentals — a set of Jupyter notebooks exploring financial data analysis, custom technical indicators, and strategy backtesting in Python.

# Overview

This repository collects my work from the Practical Investing Fundamentals module. The notebooks progress from data-handling fundamentals to building and optimizing quantitative trading strategies on real market data pulled from Yahoo Finance.
The focus is on the full analytical workflow: getting the data, engineering indicators, testing a hypothesis, optimizing parameters, and visualizing the result.

#Notebooks

| Notebook | What it covers |
| --- | --- |
| `01_pandas_numpy_basics.ipynb` | Core pandas (DataFrame indexing, filtering, sorting, plotting) and NumPy array operations. |
| `02_custom_technical_indicators.ipynb` | Downloads AAPL & NVDA data and implements three custom indicators from scratch: Psychological Line, Prime Number Bands, and Relative Volatility. Multi-axis visualization. |
| `03_bollinger_bands_backtest.ipynb` | A Bollinger Bands trading strategy with backtesting, trading-cost adjustment, cumulative returns, and grid-search optimization of take-profit / stop-loss levels. |
| `05_multi_strategy_portfolio.ipynb` | Builds a 10-stock universe and compares several strategies with parameter optimization across the portfolio. |

# Tech stack
 
`Python` · `pandas` · `NumPy` · `Matplotlib` · `seaborn` · `yfinance` · `SymPy`

# Note
 
This is academic coursework, shared as part of my data-analysis portfolio. The strategies are educational exercises and are **not** investment advice.
