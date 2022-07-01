## Time Series Forecasting


Time series components

For the purpose of choosing adequate forecasting methods, it is useful to dissect a time series into a systematic part and a non-systematic part. The systematic part is typically divided into three components: level, trend, and seasonality. The non- systematic part is called noise. The systematic components are assumed to be unobservable, as they characterize the underlying series, which we only observe with added noise.
Level describes the average value of the series, trend is the change in the series from one period to the next, and seasonality describes a short-term cyclical behavior that can be observed several times within the given series. While some series do not contain trend or seasonality, all series have a level. Lastly, noise is the random variation that results from measurement error or other causes that are not accounted for. It is always present in a time series to some degree, although we cannot observe it directly.
The different components are commonly considered to be either additive or multiplicative.
A time series with additive components can be written as: 
<br><br>
$$ yt=Level+Trend+Seasonality+Noise $$
<br>
A time series with multiplicative components can be written as: 
<br>
<br>
$$ yt=Level×Trend×Seasonality×Noise $$
<br>
Forecasting methods attempt to isolate the systematic part and quantify the noise level. The systematic part is used for generating point forecasts and the level of noise helps assess the uncertainty associated with the point forecasts.
Trend patterns are commonly approximated by linear, exponential and other mathematical functions. Illustrations of different trend patterns can be seen by comparing the different rows in the Figure below. For seasonal patterns, two common approximations are additive seasonality (where values in different seasons vary by a constant amount) and multiplicative seasonality (where values in different seasons vary by a percentage). Illustrations of these seasonality patterns are shown in the second and third columns of the figure.

