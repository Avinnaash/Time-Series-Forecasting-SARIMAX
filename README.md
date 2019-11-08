# fluffy-succotash
Time Series Forecasting Using SARIMAX

There are three trend elements that require configuration.
They are the same as the ARIMA model; specifically:

p: Trend autoregression order.

d: Trend difference order.

q: Trend moving average order.

There are four seasonal elements that are not part of ARIMA that must be configured; they are:

P: Seasonal autoregressive order.

D: Seasonal difference order.

Q: Seasonal moving average order.

m: The number of time steps for a single seasonal period.

Together, the notation for an SARIMA model is specified as:

SARIMA(p,d,q)(P,D,Q)m

Due to the nature of my dataset which i was handling, the predictions and forecast plots dont look very promising but the RMS obtained happened to be satisfactory. Also, since this dataset was real world sales data, upon comparison with the forecasted month's sales and actual sales, the prediction was quite accurate.
