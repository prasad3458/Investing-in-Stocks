Investing in Stocks

In this project, I integrated Modern Portfolio Theory (MPT), integer programming, linear regression, and Monte Carlo simulations to optimize a stock portfolio using real S&P 500 data. The primary objective was to balance risk and return by constructing portfolios that meet various risk tolerance levels.

Key components of the project:

Data Collection & Preparation:
Retrieved daily historical data for S&P 500 stocks from 2017 to 2022 using the Yahoo Finance API.
Cleaned the dataset by handling missing values and filtering out stocks with insufficient historical data.

Predictive Modeling:
Developed sector-specific linear regression models to predict the future stock value using past prices (12, 24, and 36 months).
Trained the models on 2018-2021 data to forecast 2022 performance, selecting the top 3 stocks from each sector based on predicted returns.

Modern Portfolio Optimization:
Applied integer programming to solve the MPT optimization problem using the selected stocks.
Generated the efficient frontier, which displays optimal portfolio allocations for different levels of risk, ensuring that each stock with a non-zero allocation consumed at least 2% of the total budget.
Visualized how stock allocations shifted across varying risk levels, and adjusted the model to ensure portfolios had at least three stocks, each accounting for 10% or more of the budget.

Buy-and-Hold Strategy:
Implemented a buy-and-hold strategy for the optimized MPT portfolio in 2022 and compared it with an S&P 500 index investment.
Tracked monthly returns, and provided a comparative analysis of performance.

Monte Carlo Simulation:
Ran 1000 Monte Carlo simulations using daily returns for each stock to evaluate the portfolio’s volatility and risk.
Generated density plots to assess the distribution of portfolio returns and calculated the probability of losses at both stock and portfolio levels.
