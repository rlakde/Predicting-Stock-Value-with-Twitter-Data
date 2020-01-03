## Overview

The project aims in analyzing the relationship between the fluctuations of the stock prices of a specific company with respect to the tweets about the company. We can see there are situations where the big companies' stock price drops all of sudden with one news. For example, the  Snapchat stock loses $1.3 billion after Kylie Jenner tweet. There are some scenarios where due to fake news the market reacted instantly and sharply. We would like to study the relationship between the tweets and the stock price for a company and give an analysis of what kind of tweets affect the most in positive and negative ways.

## Data

We will use live Twitter data using Twitter API about one company. Using some particular hashtags like #apple, #iphone, #airpods, etc gives good amount of data. We will be using the tweets about the company in the past weeks where the company has good fluctuations in the stock price. Problems that we will be facing are coverage problems because of the large amount of data. Other problems include text analysis and inference.

## Method

We will use sentiment analysis on Twitter data to predict the mood of the users and use the predicted mood and the previous DJIA (Dow Jones Industrial Average) values to estimate the change in the stock price. We will use classification algorithms like Naive Bayes, SVM etc to compare the accuracy. We modify the code according to the dataset and the problem.

## Related Work

Stock Market Prediction Using Twitter Sentimental Analysis:-

Link:- http://cs229.stanford.edu/proj2011/GoelMittal-StockMarketPredictionUsingTwitterSentimentAnalysis.pdf



Sentimental Analysis of twitter data for predicting stock market movements

Link:- https://arxiv.org/pdf/1610.09225.pdf

Survey: Sentiment Analysis of Twitter Data for Stock Market Prediction 

Link:- https://ijarcce.com/upload/2017/march-17/IJARCCE%20129.pdf

Stock Price Forecasting via Sentiment Analysis on Twitter

Link:- http://www.aviarampatzis.com/publications/PCI2016.pdf

The Effects of Twitter Sentiment on Stock Price Returns

LInk:- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4577113/

## Evaluation

We will give the correlation between the sentiment and the stock price. We can compare with the past stock price and the predicted stock price. The plots we produce will be the relation between the tweets and the stock price in a time interval. Accuracy will be the performance metric.

