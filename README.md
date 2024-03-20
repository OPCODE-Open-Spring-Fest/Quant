# template
A Template Repository for OpenSpringFest (OSF)

Pairs trading is a market-neutral trading strategy that involves identifying pairs of securities that are statistically likely to move in tandem and then taking a market-neutral position by buying the underperforming stock and selling the outperforming stock. The strategy relies on the mean-reverting nature of the relationship between the two stocks.

Description:

Select a Pair of Stocks: Choose a pair of stocks that are historically correlated. This can be done using statistical tests like the Augmented Dickey-Fuller (ADF) test for cointegration.
Calculate the Spread: Calculate the spread between the two stocks, which is typically the log ratio of their prices.
Determine Entry and Exit Points: Use historical data to determine entry and exit points based on the spread. Entry points are when the spread deviates significantly from its mean, indicating a potential reversion. Exit points are when the spread returns to its mean.
Implement Trading Rules: Based on the entry and exit points, implement trading rules to buy the underperforming stock and sell the outperforming stock when the spread exceeds a certain threshold.
Monitor and Rebalance: Continuously monitor the spread and rebalance the positions as necessary to maintain a market-neutral position.
