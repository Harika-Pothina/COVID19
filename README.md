# COVID19 Forecasting the cases 
HACKATHON
Pandemic Forecasting

A stable model that can forecast can act as a catalyst in better planning and to study the impacts of measures that can be taken before/during a pandemic. It not only helps in analyzing the spread of the virus, but it also helps in answering important questions related to planning, deploying ranging from “where will be the next new case”, “where are the hotspots”, “is the end near”, “how many new cases till a vaccine is effective” and “how should the vaccines be distributed”. It can also answer sustainability related questions that help decide how goods, medicines, services can be moved across the country based on current and future hotspots to its finest details.

We would combine various datasets that will help complete the picture of people’s mobility using datasets which contain information ranging from the date and numbers of cases confirmed, new, dead, recovered to movement information from various sources. We would first understand the factors that have strong correlation with the new cases using this information to provide required importance to those factors. We would also study the impact of various measures taken by the government as well as any new measures to understand how to curb the numbers of new cases.

Some models we would consider to forecast the number of confirmed cases are listed and briefed below.
 	 	 	
Holt's Linear Model
It is a smoothing model for forecasting data with trends. It has three separate equations that work together to generate a final forecast. First is a basic smoothing equation that directly adjusts the last smoothed value for last period's trend. The trend itself is updated over time through the second equation, where the trend is expressed as the difference between the last two smoothed values. Finally, the third equation is used to generate the final forecast. Holt's model uses two parameters, one for the overall smoothing and the other for the trend smoothing equation.
Holt's Winter Model for Daily Time Series
It is used to smooth a time series and use that data to forecast areas of interest. Exponential smoothing assigns exponentially decreasing weights and values against historical data to decrease the value of the weight for the older data. In other words, more recent historical data is assigned more weight in forecasting than the older results.
AR Model
A time series is a sequence of measurements of the same variables made over time. Usually the measurements are made at evenly spaced times. We forecast the variable of interest using a linear combination of past values of the variable.   
MA Model
It is used for modeling univariate time series. The moving-average model specifies that the output variable depends linearly on the current and various past values of a stochastic (imperfectly predictable) term. 
ARIMA Model
It is used for forecasting a time series which can be made to be “stationary” by differencing, perhaps in conjunction with nonlinear transformations such as logging or deflating. The model 'explains' a given time series based on its own past values, that is, its own lags and the lagged forecast errors, so that the equation can be used to forecast future values.
Facebook's Prophet Model
It is based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.
GLEAM
GLEAM produces realistic simulations of the global spread of infectious diseases. It integrates three layers: real-world data on the global population; real-world data on the mobility of this population; an individual based stochastic mathematical model of the infection dynamics.
GLEAM delivers analytic and forecasting power to address the challenges faced in developing intervention strategies that minimize the impact of potentially devastating epidemics




The above suggested models are considered on the sample datasets. In this work, different models will be implemented on the dataset to identify the confirmed cases and to forecast the cases. The model with less number of false positives and  good accuracy in identifying the confirmed COVID19 cases in various locations across India, as well as the number of resulting fatalities will be considered as the best model.



