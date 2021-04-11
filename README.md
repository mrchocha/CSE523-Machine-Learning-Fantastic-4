# CSE523-Machine-Learning-Fantastic-4
# Table of content
- Introduction
- Results
- References


# Introduction
<p>
Days back when Internet was just a dream for common people, at that time they were not surrounded by so much of information that we have now, or opinion which try to influence people’s minds and change the whole trends of stock markets and many other important markets like Gold market,even the elections in some cases. 
</p>
<p>
Here we are focusing on the stock market and its features like close price, open price, Returns, etc. And we are also establishing a relationship between trends of twitter features (Positive tweets, Negative tweets, Bullishness attitude) and stock market features (Close price, Open price, Volatility, Return) and seeing up to what extent they are correlated and if found correlatedness, we are forecasting one of the features on the basis of another using different forecasting techniques.
We have used Correlation, Granger’s Causality Analysis (GCA), Augemented Dick Fuller test (ADF test) and F-test to find relationship.
</p>
<p>
And have used forecasting techniques like ARIMA (AutoRegressive Integrated Moving Average) and OLS (Ordinary
Least Squares) Regression.
</p>

# Results
![ARIMA_forecast](https://github.com/mrchocha/CSE523-Machine-Learning-Fantastic-4/blob/main/Results/ARIMA_forecast.png)
![Correlation Matrix](https://github.com/mrchocha/CSE523-Machine-Learning-Fantastic-4/blob/main/Results/Correlation_Matrix.png)
![GCA_matrix](https://github.com/mrchocha/CSE523-Machine-Learning-Fantastic-4/blob/main/Results/GCA_matrix.png)
![OLS](https://github.com/mrchocha/CSE523-Machine-Learning-Fantastic-4/blob/main/Results/OLS.png)
![RMSE_ARIMA](https://github.com/mrchocha/CSE523-Machine-Learning-Fantastic-4/blob/main/Results/RMSE_ARIMA.png)
![seasonal_decompose](https://github.com/mrchocha/CSE523-Machine-Learning-Fantastic-4/blob/main/Results/seasonal_decompose.png)

# References
1. [Tushar Rao and Saket Srivastava, ”Analyzing Stock Market Movement Using Twitter Sentiment Analysis”](http://eprints.lincoln.ac.uk/id/eprint/11274/1/ASONAM%202012.pdf)
2. [Sentiment Analysis for Stock Price Prediction](https://towardsdatascience.com/sentiment-analysis-for-stock-price-prediction-in-python-bed40c65d178)
3. [A.Jain, P. Dandannavar, “Application of Machine Learning Techniques to Sentiment Analysis”](https://sci-hub.se/10.1109/ICATCCT.2016.7912076)
4. [Time series Forecasting using Granger’s Causality and Vector Autoregressive Model](https://towardsdatascience.com/granger-causality-and-vector-auto-regressive-model-for-time-series-forecasting-3226a64889a6)
5. [ Twitter Sentiment Analysis Applied to Finance: A Case Study in the Retail Industry](https://www.researchgate.net/publication/279864932_Twitter_Sentiment_Analysis_Applied_to_Finance_A_Case_Study_in_the_Retail_Industry)
