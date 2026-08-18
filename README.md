# Stock Market & Portfolio Analysis

## Overview

This project analyses the historical performance and risk of Apple (AAPL) and Nvidia (NVDA) using Python. It investigates returns, volatility, correlation and risk-adjusted performance, before constructing a 50/50 portfolio of the two stocks.

## Objectives

- Analyse historical stock returns

- Measure and compare volatility

- Investigate the correlation between Apple and Nvidia

- Construct a diversified 50/50 portfolio

- Compare portfolio performance with the individual stocks

- Evaluate risk-adjusted returns using the Sharpe ratio

## Technologies

- Python

- Pandas

- NumPy

- Matplotlib

- yfinance

- Jupyter Notebook

## Methodology

Daily returns were calculated using percentage changes in closing prices.

Annualised volatility was calculated using the standard deviation of daily returns multiplied by √252.

The portfolio consisted of a 50% allocation to Apple and a 50% allocation to Nvidia.

The Sharpe ratio was calculated using a risk-free rate of 3.75%.

## Results

| Metric | Apple | Nvidia | 50/50 Portfolio |
|---|---:|---:|---:|
| Total Return | 34.93% | 21.22% | 28.08% |
| Annual Volatility | 25.02% | 36.87% | 23.45% |
| Sharpe Ratio | 1.25 | 0.47 | 1.04 |

The correlation between Apple and Nvidia was approximately **0.12**.

## Conclusion

The analysis demonstrates the potential benefits of diversification.

Although Apple produced the highest total return and Sharpe ratio, the 50/50 portfolio had the lowest annual volatility at 23.45%.

The relatively low correlation between Apple and Nvidia contributed to the reduction in portfolio risk. The portfolio also achieved a higher Sharpe ratio than Nvidia, indicating better risk-adjusted performance than Nvidia alone.

## Limitations

- Historical performance does not guarantee future returns.

- The analysis covers only a one-year period.

- The portfolio assumes a constant 50/50 allocation.

- Transaction costs and taxes are not considered.

- Only two stocks are included in the portfolio.
