# Time-Series-Forecasting-and-Analysis
Time Series Forecasting is the prediction of something (price, stock prices, temperature etc.) based on historical daily data using some machine learning algorithms. It also includes analysis of the data to find out the trends and patterns in the day-to-day data.

![Prediction of Close Prices](https://github.com/ayushirastogi15/Time-Series-Forecasting-Analysis/blob/main/ClosePricePred.png)

## Why I chose to predict the market prices of a stock ?
For any investor, it is very necessary to know whether the stock prices will rise or fall in the future in which (s)he is investing. Just by looking at the balance sheets or the income statements of the company, it is hard to tell which company has a bright future and is good for investing (or trading) purposes. They should have an idea about the future prices of stock so that they cannot be in losses. And, there should be some way to know that. 

## My Solution or approach to solve this problem
So, for that and therefore, to know the prices in advance, I have worked on the Time Series Forecasting of Stock Market Prices for the next few days. In this, the model takes the historical data of stocks closing prices along with some of the technical indicators as an input. [Technical indicators](https://www.investopedia.com/terms/t/technical-analysis-of-stocks-and-trends.asp) include [SMA](https://www.investopedia.com/terms/s/sma.asp) (Simple Moving Average), [EMA](https://www.investopedia.com/terms/e/ema.asp) (Exponential Moving Average), [MOM](https://www.investopedia.com/terms/m/momentum.asp) (Momentum), [RSI](https://www.investopedia.com/terms/r/rsi.asp) (Relative Strength Index), [MACD](https://www.investopedia.com/terms/m/macd.asp) (Moving Average Convergence Divergence). These indicators help us to know the patterns or trends the stock was following. If there is an upward trend then the investor/trader should buy the stock and if there is a downward trend then they should sell the stock. 

## Metrics and Algorithms to solve that problem and Results  
So, using these features, the machine learning algorithm is trying to predict future prices. I have tried to use different ML algorithms like Linear Regression, Decision Trees, RandomForest, XGBoost, etc. And to get a better accuracy rate I have used mean_absolute_error as a metric from which we can check which algorithm is predicting accurately. The lesser the mean_absolute_error, the better the algorithm is on prediction. Above all of these algorithms, Decision Tree turns out to be the best algorithm which is giving us a higher accuracy rate of 98% on training data & 95% on testing data up to the date with mean_absolute_error as 11.22. With the hyper-parameter tuning, we can achieve lesser mean_absolute_error. 

## Conclusion
Having an idea of future stock prices could lead to better investment opportunities for investors and trading opportunities for traders as well. This approach may have an impact on the business or on the investor strategies.

