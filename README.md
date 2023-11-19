# credit-risk-classification

## Overview
The purpose of this analysis was to take a data set that contains information on healthy loans and high risk loans for deliquency and create a linear regression model that can predict whether a new loan is at high risk for deliquency. This data contains different information on loans (such as debt to income ratio and the interest rate) and is pre labeled with whether or not each loan was healthy or deliquent. This dataset contains more healthy loans than high risk loans, so we ran the model with and without a random oversample to see if we can improve the accuracy, precision, and recall.

## Results
### without oversampling
- Accuracy = 99%
- Precision = 100% for healthy and 85% for High Risk
- recall = 99% for healthy and 91% for High Risk
### with oversampling
- Accuracy = 99%
- Precision = 100% for healthy and 84% for High Risk
- recall = 99% for healthy and 99% for High Risk

## Summary
Overall, this model has a very high accuracy at detecting healthy and high risk loans. In addition, this model has a higher precision at detecting Healthy loans which means it will err on the side of Type 2 error(false-negative) instead of type 1 error. This means that if a bank were to use this model, the chances of denying a loan for someone who won't be deliquent on it is very high. I would recommend a bank to use this model based on its high accuracy and precision.