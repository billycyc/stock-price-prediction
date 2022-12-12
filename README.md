# Stock Price Prediction

## Introduction
Stock investments play an ever-increasing part in our lives and stock price prediction has been all the rage in recent years, 
in which many analysts have put much effort. Since the stock prices are volatile, they are difficult to predict accurately. 
If an accurate forecasting model can be designed, it can help stock analysts and traders to make better decisions. 

In this project, I employ univariate LSTM (Long Short-Term Memory) and CNN (Convolutional Neural Network) models to predict 
5 companies’ stock daily close price (Apple, Amazon, Google, Meta, and Microsoft). 

The exploratory data analysis of the stock historical data has been committed in [this repository](https://github.com/billycyc/stock-price-exploratory-data-analysis).

## Data Source
The stock historical data is obtained from Yahoo Finance website.   

In order to get the data directly with Python, we need to install the *yfinance* package in the environment: 
`!pip install yfinance`. Then the stock data can be downloaded by using *yfinance* package's *download()* function. 

## Notes
The models created are just prototype and further experiment are needed, thus they are still not applicable to the real market.   
In this project, only historical data is considered as the feature. However, stock prices are volatile as various factors are attributed to them, 
such as company performance, governmental regulations, market conditions, foreign investment, and natural calamities. 
Thus, it would be better to include other factors in future experiment. 
Besides, it will be ideal to also include fundamental analysis and technical analysis.  
