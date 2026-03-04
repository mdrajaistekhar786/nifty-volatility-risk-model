# NIFTY Volatility Modelling and Value-at-Risk using GARCH

## Overview

This project models financial market volatility and estimates downside risk for the NIFTY index using GARCH models.

The analysis follows a quantitative finance workflow including stationarity testing, volatility modelling, and Value-at-Risk estimation.

---

## Dataset

Source: Yahoo Finance  
Asset: NIFTY 50 Index (^NSEI)  
Period: Last 2 years of daily data  

Data is downloaded using the `yfinance` Python library.

---

## Methodology

The project follows these steps:

1. Data collection from Yahoo Finance
2. Stationarity testing using Augmented Dickey-Fuller test
3. Log return calculation
4. ACF and PACF analysis
5. Ljung-Box test for autocorrelation
6. Volatility clustering detection
7. GARCH(1,1) volatility modelling
8. Volatility forecasting
9. Value-at-Risk estimation
10. VaR backtesting
11. Kupiec test for VaR validation

---

## Key Results

- NIFTY prices are non-stationary
- Log returns are stationary
- Returns show little autocorrelation
- Volatility clustering exists
- GARCH successfully models time-varying volatility
- VaR violation rate is close to expected 5%

---

## Technologies Used

Python

Libraries:

- numpy
- pandas
- matplotlib
- yfinance
- statsmodels
- arch

---

## Files in this Repository

Quant_day_2.ipynb → Complete analysis notebook  
Quant_day_2.pdf → Exported project report  

---

## Author

Md Raja Istekhar  
Quantitative Economics and Data Science
