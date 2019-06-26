
![](usd.jpg)


# USD


Estimating Future Value of Currency Exchange Rate with Machine Learning

# Time Series
## Autoregressive Integrated Moving Average

In statistics and econometric, and in particular in time series analysis, an auto regressive integrated moving average (ARIMA) model is a generalization of an auto regressive moving average (ARMA) model. Both of these models are fitted to time series data either to better understand the data or to predict future points in the series (forecasting). ARIMA models are applied in some cases where data show evidence of non-stationarity, where an initial differencing step (corresponding to the “integrated” part of the model) can be applied one or more times to eliminate the non-stationary.
The AR part of ARIMA indicates that the evolving variable of interest is regressed on its own lagged (i.e., prior) values. The MA part indicates that the regression error is actually a linear combination of error terms whose values occurred contemporaneously and at various times in the past. The I (for “integrated”) indicates that the data values have been replaced with the difference between their values and the previous values (and this difference process may have been performed more than once). The purpose of each of these features is to make the model fit the data as well as possible.
Non-seasonal ARIMA models are generally denoted ARIMA(p,d,q) where parameters p, d, and q are non-negative integers, p is the order (number of time lags) of the auto regressive model, d is the degree of difference (the number of times the data have had past values subtracted), and q is the order of the moving-average model. Seasonal ARIMA models are usually denoted ARIMA(p,d,q)(P,D,Q)m, where m refers to the number of periods in each season, and the uppercase P,D,Q refer to the auto regressive, difference, and moving average terms for the seasonal part of the ARIMA model.
When two out of the three terms are zeros, the model may be referred to based on the non-zero parameter, dropping “AR”, “I” or “MA” from the acronym describing the model. For example, ARIMA (1,0,0) is AR(1), ARIMA(0,1,0) is I(1), and ARIMA(0,0,1) is MA(1).
ARIMA models can be estimated following the Box-Jenkins approach.

## Facebook Prophet Algorithm

https://facebook.github.io/prophet/



For More Detail: github.com/alpyts
