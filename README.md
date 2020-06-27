# Terminix Data Challenge
For Terminix Technical Exercise

## Response model

The response.csv file contains observations taken from a recent direct marketing campaign to win back former customers. 

The goal of this exercise is to 

1. Develop a predictive model to be used to select records to be included in a future campaign.

2.	Apply the model to a new dataset and select records to meet the marketing teams' cost per sale goals.
3.	Design a simple ab comparison test to understand performance differences attributable to variation in marketing treatment.

Please use SAS or R to perform this analysis.

### Part 1

Please perform the following.

1. Divide data set into training and validation sets. Set aside validation set to use only for evaluating model out of sample model performance.
2. Perform data exploration to reduce and transform the number of variables in the data set to a set of 10 predictors that look most promising for predicting sales.
3. Fit a logistic regression model to predict sales using the training data set.
4. Evaluate the performance of the model on the training set.
5. Score the validation set with the model and evaluate its performance on the validation set.

### Part 2

Assume the validation set represents a new base for selecting records to be included in the next direct marketing campaign.
Assume a cost per marketing treatment of $2. 

Select records from the scored validation set to maximize sales where the goal of the campaign is for average cost per sale to be $6.

### Part 3

The marketing team would like to test 2 variations of marketing treatment in this campaign.
Specify the minimum sample size required to detect a 5% difference in sales rate between the two treatments with 90% confidence and statistical power of 80%.