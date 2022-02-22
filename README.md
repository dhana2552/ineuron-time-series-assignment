# ineuron-time-series-assignment

## Time Series - ARIMA assignment

As part of MLDL time series assignment, it is expected to predict the sales value using an ARIMA model. The dataset contains 3 years sales data for each month. Hence the totla length is 36.

The time series analysis includes the following:
* Check missing values - Fill them with aggregate values
* Do adfuller test - to check if the data is stationary (if not, check for differencing)
* Do the time series decomposition - to check for seasonal patterns (not done here as it is not required)
* Get the ACF and PACF max parameter values from their respective plots
* Get the best ARIMA model by trying with different combinations of parameters
* Predict the future values
* Plot the results
