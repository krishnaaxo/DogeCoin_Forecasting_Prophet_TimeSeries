# DogeCoin_Forecasting_Prophet_TimeSeries

• Do ⭐ the repository if it helped you in anyway.

# Problem Statement:

Dogecoin is an open source peer-to-peer digital currency, favored by Shiba Inus worldwide. It is qualitatively more fun while being technically nearly identical to its close relative Bitcoin. This dataset contains its historical stock price in USD on a daily frequency starting from 17 September 2014.

# Data Collection:

Data is published on RBI website.

Source: https://dogecoin.com/

https://github.com/dogecoin/dogecoin

# What is Prophet?
Prophet is a facebooks’ open source time series prediction. Prophet decomposes time series into trend, seasonality and holiday. It has intuitive hyper parameters which are easy to tune.

#Advantages of using Prophet
1. Accommodates seasonality with multiple periods
2. Prophet is resilient to missing values
3. Best way to handle outliers in Prophet is to remove them
4. Fitting of the model is fast
5. Intuitive hyper parameters which are easy to tune

# Predicting the values for the future
For predicting the values using Prophet, we need to create a dataframe with ds(datetime stamp) containing the dates for which we want to make the predictions.

We use make_future_dataframe() to which we specify the number of days to extend into the future. By default it includes dates from the history

# Refrences:
1. [₿ Bitcoin Prices : EDA and Prediction (R2~0.99)](https://www.kaggle.com/kaushiksuresh147/bitcoin-prices-eda-and-prediction-r2-0-99)
2. [Ethereum EDA and Prediction using Prophet](https://www.kaggle.com/kaushiksuresh147/ethereum-eda-and-prediction-using-prophet)
3. [People's reaction on India's proposed crypto ban](https://www.kaggle.com/kaushiksuresh147/people-s-reaction-on-india-s-proposed-crypto-ban)
