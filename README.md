# AlgoTrading
Algotrading

Course Overview

Algorithmic Trading Bacics
Machine leanring in Trading
Project 1: Unsupervised Learning
Project 2: Twitter Sentiment Trading Strategy
PRoject 3: Intraday strategy Using GARCH Model
Wrap up


Youtube link: https://www.youtube.com/watch?v=9Y3yaoi9rUQ


Machine Learning In Trading 

Full use case of Machine Learning in Trading
(Supervised Learning)

1) Signal generation through machine learning prediction. For example buy or sell signal based on predicted returns of direction.
2) Risk managmement through prediction. For example determining position sizing and stop-loss levels to have more optimized risk. 

(Unsupervised Learning)
1) Extract insights from the data. For example discover patterns relationships and structures. 

Project 1: Unsupervised Learning Trading strategy

Unsuprvised Learning in trading invoves using machine learning to analyse financial data and discover patterns, relationships and structures within the data without any labeled or predefined target variables. Unlise supervided learning where mode is trained to make predictions, unsupervised learning focuses on extracting insights from the data.

Here is how unsupervised learning is applied in trading:
1) Clustering
2) Dimensionality reduction
3) Anomaly detection
4) MArket Regime detection
5) Portfolio optimization

What we will do:

1) Download S&P500 stock prices data
2) Calculate different technical indicatores and features for each stock
3) Aggregate on monthly level and filter for each month only top 150 most liquid stocks
4) Calculate monthly retiurns for different time-horizons to add to features
4) Download Fama and French factors and calculate rolling factor betas for each stock
5) For each month fit a K-means clustering model to group similar assets based on their features
6) For each month select fit assets based on the cluster and form a portfolio based on Efficient Frontier max  sharpe ratio portfolio optimization
7) Visualize the portfolio returns and compare to S&P500 returns

Limitations: There may be survivorship bias in the list. In real world we should use surbiviorship free data. More information on surbiviorship bias can be found here: https://www.investopedia.com/terms/s/survivorshipbias.asp#:~:text=Survivorship%20bias%20or%20survivor%20bias,those%20that%20have%20gone%20bust.


Fama and French Three Factor Model Definition: https://www.investopedia.com/terms/f/famaandfrenchthreefactormodel.asp#:~:text=of%20the%20Model%3F-,The%20Fama%20and%20French%20model%20has%20three%20factors%3A%20the%20size,risk%2Dfree%20rate%20of%20return.


Project 2: Twitter Sentiment Trading Strategy




Project 3: Intraday strategy Using GARCH Model
