# Stock-Forecasting-Prophet
Stock price forecasting for Reliance Stock using FBProphet.

**Disclaimer - The code in this repository is just for learning purposes, and you should never use this to invest/trade any stock, because there are a lot of other factos that govern
the price of a stock, which are beyond past performances, having said that, I am not responsible for any profit/loss you make using this to make decisions, I strongly discourage anyone from doing that.**

* There are a lot of Time series forecasting methods available, and Deep-Learning based forecasts using LSTM are quite popular, however I think that Prophet, by Facebook is an amazing open source library, which is 
often underestimated and can be used
for making really amazing and accurate forecasts, specially if the **time series has strong seasonal effects and several seasons of historical data**.

* In this running example, we forecast the closing price of Reliance's Stock(Yahoo Ticker : RELIANCE.NS), which is India's largest publically listed company(according to Market cap), listed on both
NSE(National Stock Exchange) and BSE(Bombay Stock Exchange). This example can be used a boilerplate for any time-series forecasting, and remember, Prophet works amazingly well if you data has a strong seasonality.

* **Are stock prices Seasonal?** - The answer to that is both Yes and No, in short, it highly depends.
Therefore, one of the best use-cases of Prophet might be Forecasting Sales of an E-Commerce company, or in general, any time-series that has a strong seasonal component.



Feel free to play around with this code, happy learning!
