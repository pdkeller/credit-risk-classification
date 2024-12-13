# credit-risk-classification
# Author: Paul Keller
# Submission Date: December 12, 2024

This logistic regression model is used to test the reliability of healthy loans and high-risk loans. The data set being tested was a collection of loans made out to lendees that the size of the loan, the interest rate, total debt, and total income among several features. Also included was the label assigned to each lendee: 0 (a healthy loan) and 1 (a high-risk loan). This data set was split into training and testing data sets and then the logistic regression model that was created was run on this data sets and the predictions of labels for each lendee was assigned based on the model.

The results of the machine learning model:
    *Accuracy Score: 99%
    *Precision Score: 92%
    *Recall Score: 97%
The precision and recall scores were both macro-averaged.

Based on the initial results, I would reccomend the use of this model to predict labels to give to potential lendees. First, I would want to run more tests on this model in order to gain more confidence in its ability. It should be noted that this model is better at predicting true healthy loans over high-risk loans because the precision scores are 100% for healthy loans and 84% for high risk-loans and the recall scores are 99% for healthy loans and 94% for high-risk loans. Based on these results, I feel that what has been shown by this logistic regression model so far is promising.
