# Analyzing Stock Market Volatility Patterns Using Historical Data

## Overview
This project analyzes one year of daily Apple (AAPL) stock price data (Sept 2024–Sept 2025) 
to identify short-term volatility patterns and evaluate whether average daily returns differ 
significantly from zero.

## Methods
- Data collected programmatically via the `yfinance` API
- Data cleaning and preparation using Pandas
- Descriptive & diagnostic analysis: daily returns, rolling volatility, moving averages, 
  weekday volatility comparisons
- One-sample t-test (SciPy) to test whether mean daily return significantly differs from zero
- Visualizations built with Matplotlib and Seaborn
- Followed the CRISP-DM methodology end to end

## Key Findings
- No statistically significant difference from zero in average daily returns (t = 0.40, p = 0.69)
- Despite this, meaningful volatility patterns emerged — including periods of elevated rolling 
  volatility and variation in volatility across weekdays — with practical implications for 
  short-term risk management

## Tools
Python, Pandas, Matplotlib, Seaborn, SciPy, yfinance, Jupyter Notebook

## Files
- `Polskaya_Capstone.ipynb` — full analysis and code
- `Polskaya_Task3.pdf` — written report
- `Polskaya_Capstone.pdf` — pdf version of ipynb file
