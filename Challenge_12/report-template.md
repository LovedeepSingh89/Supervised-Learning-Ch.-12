# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge.

* Explain the purpose of the analysis.
I am using a supervised learning model to predict credit risk for consumer loans

* Explain what financial information the data was on, and what you needed to predict.
Trying to predict credit risk by using a classification algorithm 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
I am predicting the 'loan_status' variable, by using features provided by the data which are labeled to predict safe versus risky loans

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method). 
I use Logistic Regression because it is designed to predict discrete outcomes. The dataset is highly imbalanced so I had to use the RandomOverSampler method to balance out the distribution of healthy and high risk loans

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
accuracy - With the imbalanced data and model, is 99%, 
precision - of almost 100% prediction on healthy loans and about 84% on high risk loans
recall - of almost 99% prediction on healthy loans and about 92% on high risk loans


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

With creating more instances of the smaller class, accuracy and precision stayed the same, but recall improved at predicting high risk loans


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?

I recommend using the second model because the data isn't imbalanced and it has a higher recall percentage while having the same accuracy and precision as the first model 

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

In this situation it would be important to predict the 1's - high risk loans. 
