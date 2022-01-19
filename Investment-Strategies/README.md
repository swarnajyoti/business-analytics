<h1 align="center">Investment Strategies</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/bitbucket/issues-raw/swarnajyoti/business-analytics)](https://github.com/swarnajyoti/business-analytics/Investment-Strategies/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-raw/swarnajyoti/business-analytics)](https://github.com/swarnajyoti/business-analytics/Investment-Strategies/pulls)
[![License](https://img.shields.io/github/license/swarnajyoti/business-analytics)](/LICENSEMIT)

</div>

# Analysis of Asset Allocation Strategies for Investing

This repository contains a data driven approach for analyzing asset allocation strategies for investing using python and its core libraries, particularly, NumPy, Pandas, Matplotlib, Plotly, IPython, scipy.stats, and related packages.

I have explored what I would call continuous asset allocation (allocating regular contributions among your investments) and seasonal asset allocation (allocating entire contributions to specific investments based on seasonal trends). The goal would be to determine which approach, if either, produces better long-term returns. For example, for a given year, if I want to contribute 50% of my $100 monthly investments to stocks (e.g., S&P 500) and 50% to fixed income (e.g., Treasury bills), should I contribute $50 and $50, respectively, each month, or choose 6 months for each investment to contribute the full $100?

So, I started by pulling historical data of Thrift Savings Plan which has generalized mutual fund for each of these components - G, F, S, C, I plus lifecycle funds that I will ignore. The next step was to calculate monthly returns by calculating the percent change from the previous month (using the 1st of each month). The remainder of the project went ahead something like this: deciding on asset allocation (what percent to invest in each fund); specifying investment window (e.g., 1, 5, 10, 25 years); running ‘n’ simulations for both strategies (continuous vs seasonal); and computing output statistics on performance (e.g., mean savings at end of investment window, histogram of mean savings across ‘n’ replications).

## Percentage Monthly Returns Distribution for C Fund
![aa](https://github.com/swarnajyoti/business-analytics/blob/main/Investment-Strategies/Image/Percentage%20Monthly%20Returns%20Distribution%20for%20C%20Fund.png)

## Percentage Monthly Returns Distribution for F Fund
![bb](https://github.com/swarnajyoti/business-analytics/blob/main/Investment-Strategies/Image/Percentage%20Monthly%20Returns%20Distribution%20for%20F%20Fund.png)

## Percentage Monthly Returns Distribution for G Fund
![cc](https://github.com/swarnajyoti/business-analytics/blob/main/Investment-Strategies/Image/Percentage%20Monthly%20Returns%20Distribution%20for%20G%20Fund.png)

## Percentage Monthly Returns Distribution for I Fund
![dd](https://github.com/swarnajyoti/business-analytics/blob/main/Investment-Strategies/Image/Percentage%20Monthly%20Returns%20Distribution%20for%20I%20Fund.png)

## Percentage Monthly Returns Distribution for S Fund
![ee](https://github.com/swarnajyoti/business-analytics/blob/main/Investment-Strategies/Image/Percentage%20Monthly%20Returns%20Distribution%20for%20S%20Fund.png)
