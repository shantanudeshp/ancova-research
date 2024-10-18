# ancova-research
research project as part of ancova capital management. thesis is to determine the effects of individual stocks and sector performance on the overall market, and then backpropagate those results in order to predict the performance of individual stocks and sectors.

## 10/18/24
Downloaded historical data for the S&P100 (OEX) that tracks 100 large-cap blue-chip stocks from the S&P500. Data was tabulated in the form of a single combined csv as well as individual csv files in the 'stocks' folder.

Also computed summary statistics for the data:
- annualized return
- annualized volatility (daily standard deviation * square root of 252, the number of trading days in a year)
- maximum drawdown (largest peak-to-trough decline of a given stock)
- Sharpe ratio (using 4% for RFRR. this value can be edited in the notebook)

These statistics can help to provide a general overview of the risk of any given investment, as well as a general overview of normalized returns relative to volatility. A widget in the notebook enables easy sorting and visualization of the various metrics.