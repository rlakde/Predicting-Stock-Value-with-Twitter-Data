# ANALYSIS OF CHANGES IN THE STOCK PRICE WITH RESPECT TO TWEETS

See [Instructions.md](Instructions.md) to get started.

# Introduction
Our project deals with finding the relationship between the stock price of a given company with respect to tweets about the company. We had choosen to work on the stock price of Apple company by retriving the tweets about Apple. So, we’ve categorized all the tweets into three categories namely tweets by the company itself, tweets by influential people and tweets by noninfluential people. We have applied a sentimental analysis to find the correlation between public sentiment and market sentiment. We used Twitter data to predict the public mood and use the predicted mood and the previous stock price values which are obtained from yahoo finance to predict the stock market movements.

# Data
```bash
Steps for data collection
1. The inputs.csv file is uploaded where the inputs must be provided, the time_limit field is the number of hours to collect the data and train the model, by default it is 1min. The cc and max_days are the min and max days between which we can collect data. It should be within one week. Start and end date are for stock data for which you want to collect stock price. 
2. Make sure the input dates for stock data and twitter data should match.
3. For twitter we used tweepy package to collect tweets and for stock data we used yfinance package.
4. For twitter data collection the functionality is provided which collects the data based on the trending products listed for that company.
```
# Methods

```bash
-> Data collected.
-> Pre processed the data.
-> Decided to use tweets for Apple only from influential people.
-> Observed the patterns in data using different approaches, which includes multiple linear regression, time-series analysis using Tensorflow and FbProphet.
-> Selected the best fit model which is Multiple linear regression.
-> Obtained the intercepts and respective coefficients for predictors.
-> Splitted the data into test and train.
-> Trained the model on one week of data.
-> Tested the results for a day which is not in the train set.
-> Collected the live data from twitter, analysed it and predicted the future stock value.
```

Workflow diagram:- [https://github.com/iit-cs579/project-harikajetti/blob/master/img/WORKFLOW.jpg] <br/>
Tensorflow result:-[https://github.com/iit-cs579/project-harikajetti/blob/master/img/Tensorflow.png] <br/>
FBProphet result:-[https://github.com/iit-cs579/project-harikajetti/blob/master/img/Fbprophet.png] <br/>
Regression result:- [https://github.com/iit-cs579/project-harikajetti/blob/master/img/Multipleregression.png] <br/>
# Results

```bash
RMSE of the model = 0.3821
```
Evaluation result:- (https://github.com/iit-cs579/project-harikajetti/blob/master/img/evaluate.png)

```bash
Sample Predicted stock price:- 264.13
Sample Actual stock price:- 264.48
```
Plot for the estimated model:- [https://github.com/iit-cs579/project-harikajetti/blob/master/img/regression.png]
