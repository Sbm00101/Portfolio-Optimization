
# Portfolio Optimization

## Overview
This project focuses on optimizing a portfolio of Indian stocks using historical data and Monte Carlo simulations. The goal is to maximize the Sharpe Ratio, balancing risk and return, to identify the most efficient portfolio allocation.

## Tech Stack
- Python: Core language used for all computations and data handling.
- NumPy: Used for numerical calculations, particularly in generating random portfolio weights and computing log returns.
- Pandas: Employed for data manipulation, time series management, and handling large datasets efficiently.
- Matplotlib & Seaborn: Utilized for data visualization, specifically to plot risk-return profiles and Sharpe Ratios.
- yFinance: API used to fetch historical stock data for analysis.

## Project Details
- Stocks Analyzed: RELIANCE.NS, TCS.NS, HINDUNILVR.NS, HDFCBANK.NS, ITC.NS, LT.NS, INFY.NS.
- Time Frame: October 2018 - October 2023.
- Simulations: 10,000 Monte Carlo simulations were performed to explore a wide range of potential portfolio allocations.

## Optimization Results:
- Best Sharpe Ratio: 0.81
- Expected Return for Optimal Portfolio: 16.32%
- Expected Risk: Quantified through the portfolio's standard deviation.


## Visualization
The project includes a scatter plot of portfolios, where:
- X-axis: Expected Risk
- Y-axis: Expected Return
- Color: Indicates the Sharpe Ratio
This visualization helps in identifying the most efficient portfolio.

## Conclusion
The project successfully demonstrates portfolio optimization using historical data and statistical techniques, providing a robust foundation for making informed investment decisions.


