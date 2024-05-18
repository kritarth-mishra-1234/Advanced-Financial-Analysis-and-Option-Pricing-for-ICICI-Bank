# Advanced-Financial-Analysis-and-Option-Pricing-for-ICICI-Bank

This project encompasses a thorough examination of ICICI Bank stock data and the pricing of European options using various quantitative methods.

## Overview

- **Data Collection:** Utilized Yahoo Finance to download historical ICICI Bank (ICICIBANK.NS) stock data in CSV format.
- **Data Visualization:** Plotted stock prices and log-returns to gain insights into the underlying trends and volatility.
- **Statistical Analysis:** Employed QQ plot, histograms, and statistical tests (e.g., Jerq-Berra, Kolmogorov-Smirnov) to assess the normality of log-returns.
- **Volatility Estimation:** Calculated historical volatility based on log-returns and identified the risk-free rate for the currency.
- **Correlation Testing:** Examined the assumption of independent/uncorrelated log-returns to evaluate risk factors.
- **Option Pricing:** Utilized Cox-Ross-Rubinstein (CRR), Black-Scholes, and Simulation methods to compute European call and put option prices.
- **Advanced Volatility Models:** Implemented GARACH, Heston, and Mimbian models for volatility estimation.

## Project Structure

- `data/`: Folder containing downloaded ICICI Bank stock data in CSV format.
- `notebooks/`: Jupyter Notebook files for data analysis and option pricing.
- `results/`: Directory for storing outputs such as plots and statistical test results.
- `README.md`: Project overview and instructions for replicating the analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries (numpy, pandas, matplotlib, scipy, etc.)
