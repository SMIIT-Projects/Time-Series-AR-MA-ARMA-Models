# Time-Series Models-AR, MA, ARMA.

### Auto Regression:

Auto regression is a time series model that uses observations from previous time steps as input to a regression equation to predict the value at the next time step. It is a very simple idea that can result in accurate forecasts on a range of time series problems. A statistical model is autoregressive if it predicts future values based on past values. Auto regression analysis is a standard technique in signal processing where a linear predictor estimates the value of each sample of a signal by a linear.

### What is Lag in a time series:

A “lag” is a fixed amount of passing time; One set of observations in a time series is plotted (lagged) against a second, later set of data. The kth lag is the time period that happened “k” time points before time i. For example:
Lag1(Y2) = Y1 and Lag4(Y9) = Y5.

### What is ACF and PACF in time series?

A time series can have components like trend, seasonality, cyclic and residual. ACF considers all these components while finding correlations hence it's a 'complete auto-correlation plot'. PACF is a partial auto-correlation function.

### Autoregressive (AR) models
In a multiple regression model, we forecast the variable of interest using a linear combination of predictors. In an auto regression model, we forecast the variable of interest using a linear combination of past values of the variable. The term auto regression indicates that it is a regression of the variable against itself.

### Moving Average (MA) Model
In time series analysis, the moving-average model, also known as moving-average process, is a common approach for modelling univariate time series. The moving-average model specifies that the output variable depends linearly on the current and various past values of a stochastic term.

### Autoregressive Moving Average (ARMA)

In the statistical analysis of time series, autoregressive–moving-average (ARMA) models provide a parsimonious description of a (weakly) stationary stochastic process in terms of two polynomials, one for the auto regression (AR) and the second for the moving average (MA).
ARMA (p, q) models have a rich history in the time series literature, but they are not nearly as common in ecology as plain AR(p) models. As we discussed in lecture, both the ACF and PACF are important tools when trying to identify the appropriate order of p and q. Here we will see how to simulate time series from AR(p), MA(q), and ARMA (p, q) processes, as well as fit time series models to data based on insights gathered from the ACF and PACF.

### Data Source:
https://github.com/SMIIT-Projects/Time-Series-AR-MA-ARMA-Models

### Tools and Technologies:
The Code is written in Python 3.8.5.

### Used libraries:
numpy==1.20.1
pandas==1.2.3
matplotlib==3.3.4
seaborn==0.11.1
statsmodels==0.12.2

