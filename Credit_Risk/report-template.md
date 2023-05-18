## Credit Risk Classification Analysis 

## Overview of the Analysis

This dataset is reviewing historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditwrothiness of borrowers. This model is intended to determine the liklihood of a loan being a healthy loan or a high risk of default. 

In this analysis the loan status was separated from the remaining columns in the dataframe. The value_counts function is used to determine how many healthy (0) and high risk of defaulting (1) loans. The data was split into training and testing datasets. The train data was fit to a logistic regression model and predictions were saved. The model performance was evaluated through an accuracy score, confusion matrix, and printed as a classification report. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
      *Accuracy = 0.952
      *Precision: 0 = 1.00, 1 = 0.85
      *Recall: 0 = 0.99, 1 = 0.88

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
      *Accuracy = 0.994
      *Precision: 0 = 1.00, 1 = 0.84
      *Recall: 0 = 0.99, 1 = 0.99

## Summary

I would only recommend using this model to do an initial filter of loans that are analyzed as healthy. Any loans that were assigned to a high risk default (1) by the model should have additional analysis knowing that the model is less precise when assigning this designation. 