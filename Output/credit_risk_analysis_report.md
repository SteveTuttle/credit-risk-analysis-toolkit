# Module 12 Credit Risk Analysis Report

## Overview of the Analysis

For this analysis, the aim was to develop machine learning models to predict loan statuses based on various financial features. The data consisted of information on loan sizes, interest rates, borrower income, debt-to-income ratios, number of accounts, derogatory marks, and total debt.

The goal was to predict whether a loan would be classified as a healthy loan (0) or a high-risk loan (1). The dataset was imbalanced, with a significantly higher number of healthy loans than high-risk loans.

* Number of healthy loans (0): 75,036
* Number of high-risk loans (1): 2,500

We followed these stages in the machine learning process:

1) Data Preprocessing: We split the data into features (`X`) and labels (`y`) and further divided it into training and testing sets using the `train_test_split` function.
2) Model Selection and Training: We employed two models for prediction:
    * __Model 1:__ Logistic Regression
    * __Model 2:__ Random Forest model
3) Prediction and Evaluation: The models were used to predict loan statuses for the testing data. We evaluated their performance using various metrics, including the balanced accuracy score, precision, recall, and the confusion matrix.

## Results

* __Machine Learning Model 1: Logistic Regression__
    * Balanced Accuracy Score: 0.9443
    * Precision (healthy loans): 1.00
    * Precision (high-risk loans): 0.87
    * Recall (healthy loans): 1.00
    * Recall (high-risk loans): 0.89

- - - - - - - - - - - - - - - - - - - - - - - - - -

* __Machine Learning Model 2: Random Forest Model__
    * Balanced Accuracy Score: 0.9443
    * Precision (healthy loans): 1.00
    * Precision (high-risk loans): 0.88
    * Recall (healthy loans): 1.00
    * Recall (high-risk loans): 0.88

## Summary

The Logistic Regression model (__Model 1__) and the Random Forest model (__Model 2__) both demonstrated strong performance in predicting loan statuses. They achieved the same balanced accuracy score of 0.9443, indicating that they effectively balanced precision and recall for both healthy and high-risk loans.

The performance of the models depends on the specific problem we are trying to solve. In our case, the balanced accuracy score indicates that both models are effective in predicting both healthy and high-risk loans, which is essential for maintaining a balanced assessment of loan status.

Given their strong performance, we recommend using either the Logistic Regression model or the Random Forest model for predicting loan statuses. Their ability to accurately predict both healthy and high-risk loans makes them suitable choices for this analysis. However, from a sheer coding perspective, the Logistic Regression model may be more convenient and expedient given the results.

Overall, the balanced accuracy, precision, and recall scores collectively demonstrate the efficacy of the models in making predictions for loan statuses.
