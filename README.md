# Value_at_Risk_Forecasting
The introduction of derivative instruments and several financial recessions in the last few decades has prompted the financial industry and regulators to develop new methods to measure the potential losses associated with their portfolios and Investments. The following paper proposes a new model for measuring value at risk, a conditional metric for measuring the potential portfolio losses in adverse market conditions. In this paper, we develop volatility estimation models by combining the forecasting abilities of multiple well-known generalized autoregressive conditional heteroscedasticity (GARCH)-type models with deep learning models to analyze and predict exponential-based rolling volatility. The volatility estimated by these models is then used to measure the market risk of a portfolio of assets, called Value at Risk (VaR). VaR depends on the volatility, time horizon, and confidence interval for the continuous returns under analysis. For empirical assessment, we compare the results of this approach across several parametric(Variance VaR, Historical) and nonparametric approaches(Bootstrap, FHS, Vol. Wgt, Age Wgt.) using different error functions to measure the backtesting accuracy. The risk analysis is conducted by backtesting the three approaches by computing the one-day VaR forecast for S&P 500, USD/Euro, and Crude Oil and looking at the violations to compare the efficiency of these models. The results are calculated using a 252 rolling window size and tested at the 1% and 5% significance levels based on the Student-t distribution, which provided more accurate results than the Gaussian distribution. The hybrid models produce superior forecasts compared to the conventional forecasting models for producing volatility and other parametric approaches for computing the VaR.
