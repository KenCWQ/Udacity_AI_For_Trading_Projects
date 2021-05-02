# Udacity Nanodegree - Artificial Intelligence For Trading Projects
This repository contains the projects I have completed for the Udacity Nanodegree: Artificial Intelligence for Trading.

Description of each projects as follows:

<b>1. Trading with Momentum</b>

Implemented a trading strategy and tested to see if it has the potential to be profitable with a supplied universe of stocks and time range.
A trading signal was generated based on a momentum indicator, and then computed the signal for the time range given and applied it to the dataset to produce projected returns. 
Finally, a statistical test was performed on the mean of the returns to conclude if there is alpha in the signal.
End of day dataset from Quotemedia was used.

<b>2. Breakout Strategy</b>

A breakout strategy was implemented with the additional task of finding and removing any outliers.
the strategy was tested to see if it has the potential to be profitable using a Histogram and P-Value.
End of day dataset from Quotemedia was used.

<b>3. Smart Beta and Portfolio Optimization</b>

Built a smart beta portfolio and compared it to a benchmark index, calculated the tracking error against the index to find out how well the smart beta portfolio did.
The portfolio was subsequently built by using quadratic programming to optimize weights, performed rebalancing of the portfolio and calculated the turn over to evaluate the performance. 
End of day dataset from Quotemedia was used.

<b>4. Alpha Research and Factor Modelling</b>

Built a statistical risk model using PCA.
The model was later used to build a portfolio along with 5 alpha factors which are created and evaluated using factor-weighted returns, quantile analysis, sharpe ratio and turnover analysis.
The portfolio was optimized using the risk model and factors using multiple optimization formulations.
End of day dataset from Quotemedia and sector data from Sharadar were used.

<b>5. NLP on Financial Statements</b>

A NLP analysis was done on 10-k financial statements to generate an alpha factor. End of day dataset from Quotemedia and Loughran-McDonald sentiment word lists were used

<b>6. Sentiment Analysis with Neural Networks</b>

A deep learning model was built to classify the sentiment of messages from StockTwits, a social network for investors and traders. 
The model is able to predict if any particular message is positive or negative and thus able to generate a signal of the public sentiment for various ticker symbols.

<b>7. Combining Signals for Enhanced Alpha</b>

Built a random forest to generate better alphas through combination of signals. For the dataset, the end of day from Quotemedia and sector data from Sharadar were used.

<b>8. Backtesting</b>

Built a fairly realistic backtester that uses the Barra data. 
The backtester performs portfolio optimization that includes transaction costs. Implementation was considered for computational efficiency to allow for a reasonably fast backtest. 
Performance attribution was used to identify the major drivers of your portfolio's profit-and-loss (PnL). 
