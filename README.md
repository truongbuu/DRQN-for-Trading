# DRQN-for-Trading

Final Project for Reinforcement Learning course CS885 at the University of Waterloo.

The agent are able to perform well on the data that is similar to the training data. It fails to compete against the Hold strategy on the extreme bullish period since the training data has small amount of such bullish data. It is good at sideway trading, moderate bullish and know to stop loss in bearish scenario. Further improvement required. The features are inspired from the Udacity Machine Learning for Trading course. 


This project implements DRQN for trading.[Hausknecht, Matthew, and Peter Stone. "Deep recurrent q-learning for partially observable mdps." CoRR, abs/1507.06527 7.1 (2015).]

The file technical_indicator.py is imported from https://github.com/Crypto-toolbox/pandas-technical-indicators/blob/master/technical_indicators.py .

The model is inspired from Pytorch example: https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html

