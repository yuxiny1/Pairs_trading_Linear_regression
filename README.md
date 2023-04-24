# Pairs_trading_Linear_regression
1. Introduction
The project focuses on utilizing pairs trading as an investment strategy to enhance investor returns. Pairs trading is a market-neutral trading strategy that matches a long position in one stock with a short position in another highly correlated stock. The primary objective is to capitalize on temporary price discrepancies between the two stocks while minimizing market risk. This report provides an overview of the experimental approach, testing methodology, and measurable achievements related to the project.
1.1 Project Summary and Context
The project aims to help investors comprehend the fundamentals of pairs trading and demonstrate how to employ this strategy to increase their likelihood of generating profits. The methodology involves using linear regression, machine learning techniques, and Long Short-Term Memory (LSTM) models to analyze stock price relationships and make informed trading decisions.
1.2 Experiment Overview
The experiment begins by selecting a basket of stocks from Yahoo Finance and using a heatmap to analyze the correlation between stock prices. The PepsiCo (PEP) and Coca-Cola (KO) stocks are identified as highly correlated with a correlation coefficient of 0.96. The data is then preprocessed and assessed for suitability.
1.3 Methodology
The whole methodology involves the following steps:
1. Calculate the change in stock prices for PEP and KO, creating a matrix for the independent variable (X) and the dependent variable (Y).
2. Determine the linear relationship between the changes in the two stock prices. 3. Apply linear regression to calculate the spread between the stock prices.
4. Accumulate the changes in the spread and perform linear regression to derive alpha and beta values again.
5. Calculate the mean and standard deviation of the cumulative spread to better understand long- term trends.
6. Develop a trading strategy based on the spread between PEP and KO stock prices.
7. Evaluate the strategy's profit and loss, as well as various performance metrics, to gauge its effectiveness.
1.4 Measurable Achievements
The project aims to achieve the following measurable outcomes:
- Simulate trading and predict the stock prices of two stocks.
- Measure different models of profit in different perspectives for pairs trading.
- Compare results of different models to evaluate the accuracy and error rate of the trading strategy.
By providing a comprehensive understanding of pairs trading and a tested methodology for implementing the strategy, this project aims to assist investors in maximizing their returns while minimizing risk
