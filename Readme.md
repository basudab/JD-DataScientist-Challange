## Details
on this problem statement, I used the RFM model Which is Recency, frequency, monetary value is a marketing analysis tool used to identify a company's or an organization's best campaign by using certain measures. The RFM model is based on three quantitative factors, but as per the dataset, I used two factors- 

Recency: How recently a campaign has made an activity
Frequency: How often a campaign makes a activity

## The Significance of Recency, Frequency Value
RF analysis allows a comparison between potential contributors or clients. It gives organizations a sense of how much revenue comes from repeat customers (versus new customers), and which levers they can pull to try to make customers happier so they become repeat purchasers.


## Ovservation - 
My aspect that influence responsiveness globally is the quality of the campaign - how it is appealing to the users. That could be partially inferred observing responsiveness of users when they receive various campaigns at the same times of the day.

That poses a question what is the distribution of the times of the day each campaign separately and in comparison between them - whether there is enough data to try to infer that information.

## Prediction

As per the task i like to use probalistic model to predict the outcome-

## Logistic Regression Overview
Logistic regression is a fundamental classification technique. It belongs to the group of linear classifiers and is somewhat similar to polynomial and linear regression. Logistic regression is fast and relatively uncomplicated, and it’s convenient for you to interpret the results. Although it’s essentially a method for binary classification, it can also be applied to multiclass problems. 
Also our problrm is binary so it's could be good fit.

## Why did you choose the algorithm?
Logistic regression is the type of regression analysis used to find the probability of a certain event occurring. It is the best-suited type of regression for cases where we have a categorical dependent variable that can take only discrete values.

our problem is probabilistic and binary, we had to find the  Activity Type - which is #Good or #Bad.

logistic regression is simple and the best fit for this kind of problem.   

## What are missing information, what do we need to get more from the company?

There is not clear how cases, when the user has not responded, are modeled and/or whether each campaign/activity_type has been sent to all users.