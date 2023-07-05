# Markowitz Portfolio Management

Learnt about the **Markowitz Portfolio Theory** which diversifies portfolio to earn a particular return while minimising the risk taken. Implemented the same in python by analysing the [NIFTY 50 stocks dataset](./nifty50.csv) and evaluated the obtained portfolio against the Nifty 50 benchmark.

## [Assignment 1](./assignment_1/)
+ Processed the [NIFTY 50 stocks dataset](./nifty50.csv) (Time period : 01/01/2016 - 31/12/2020) using `Numpy` and `Pandas` libraries.
+ Calculated the **volatility**, **CAGR(Compounded Annual Growth Rate)** and **Sharpe Ratio for the stock price series**.
+ Identified the top 15 stocks having the highest Sharpe Ratio. The aim was to look for stocks having high returns with low risk.

## [Assignment 2](./assignment_2/)
+ Initialised 600000 random weights(to have a large representative sample) for the 15 stocks and calculated the Expected Return(taken equal to the CAGR), Volatility and Sharpe Ratio corresponding to the weights.
+ Identified the Max Sharpe Ratio of the portfolio from the random weights and plotted the Return and Volatility of the portfolios on a **Scatter Plot** using `Matplotlib`.
+ Plotted the **Efficient Frontier** using **SLSQP method**. 
+ Taking the total amount as 10000000, obtained the amount of money to be invested in each stock and the number of shares held for them.

## [Assignment 3](./assignment_3/)
+ Tested the portfolio on time period 01/01/2021 - 30/06/2021. 
+ Scraped the required data from Yahoo using `Pandas data reader`.
+ Evaluated the portfolio on the following metrics :
    1) Total Return on Portfolio
    2) Volatility
    3) Beta
    4) Sharpe Ratio
    5) Jenson's Alpha
    6) Sortino/Treynor Ratio

These metrics were compared with the benchmark, i.e. Nifty 50.