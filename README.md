# Dual-Class Share Arbitrage

Team Members:
- [Cheuk Yan Fung (Pi)](github link)
- [Seyed Abdolhamid Banihashemi](https://github.com/sabani1998)
- [Sepehr Mohammadkhani](https://github.com/SeperMan-late)



## Project Overview

### **Introduction**

Lennar is dual-listed under the tickers LEN and LEN-B. Historically, driven by liquidity premiums and LEN’s inclusion in the S&P 500, LEN-B has traded at a discount. We observed a historical spread ranging from 2% to 25%, with a structural regime shift post-2017 that compressed the discount to a tighter 5% to 10% range. Given that LEN and LEN-B pay the same dividend and each LEN-B share holds ten times the voting power of a LEN share, we investigated whether a viable arbitrage opportunity exists.

### **Repository Structure**

Contained in `data` folder:
- `Closing_prices.csv`: Closing price data for the shares.
- `cleaned_div.xlsx`: Dividend data obtained from ???.

Contained in `scripts` folder:
- `data_import.ipynb`: Imports data from Yahoo!Finance in the time horizon of July 1st 2013 to June 18th 2026.
- `data_exploration.ipynb`: Explores the spread between the shares and their cointegration.
- `strategies.ipynb`: Contains various trade strategies. 



## Dependencies
Numpy, Pandas, Scikit-Learn, Matplotlib, YFinance, Statmodels

## Contact

Cheuk Yan Fung (Pi) - [email]

Seyed Abdolhamid Banihashemi - sabani@umd.edu

Sepehr Mohammadkhani - [email]
