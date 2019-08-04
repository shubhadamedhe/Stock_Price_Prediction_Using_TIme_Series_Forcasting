# Stock_Price_Prediction_Using_TIme_Series_Forcasting

This repository aims to predict stock price of Microsoft stock using time series forcasting methods. We will import data, visualize the time series data and use following time series forcasting methods.

The code in the notebook was executed using python 3.6; the following python libraries were used throughout the project:

    - numpy
    - pandas
    - matplotlib
    - datetime
    - seaborn
    - sklearn
    - statsmodels

### Data Source

We are using data of Microsoft stock from 2011/01/01 to 2019/07/31

### Conclusion
We have implemented following models for stock price prediction.
     
    - Simple moving average
    - Simple exopnential smoothing
    - Holt's linear method
    - Holt's winter method
    - ARIMA
From all the above model, holts linear model performed best. It has RMSE of 5.89. We can implement Seasonal ARIMA also for better results.
