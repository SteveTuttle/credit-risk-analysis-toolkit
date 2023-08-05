# credit-risk-classification
UNC_data_bootcamp_module_20

## Challenge Description
### Background
> For this Challenge, we are going to use various techniques to train and evaluate a model based on loan risk. We will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

***from the UNC Bootcamp instructions for this challenge***

## Deliverables
This challenge is broken down into three subsections --- (update each section)
* Split the Data into Training and Testing Sets
* Create a Logistic Regression Model with the Original Data
* Write a Credit Risk Analysis Report


### Part-1: Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

1) Read the _lending_data.csv_ data from the Resources folder into a Pandas DataFrame.

2) Create the labels set (_y_) from the “loan_status” column, and then create the features (_X_) DataFrame from the remaining columns.

  * __NOTE:__ A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

3) Split the data into training and testing datasets by using _train_test_split_.



### Part-2: Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

1) Fit a logistic regression model by using the training data (_X_train_ and _y_train_).

2) Save the predictions for the testing data labels by using the testing feature data (_X_test_) and the fitted model.

3) Evaluate the model’s performance by doing the following:

  * Generate a confusion matrix.

  * Print the classification report.

4) Answer the following question: How well does the logistic regression model predict both the __0__ (healthy loan) and __1__ (high-risk loan) labels?




### Part-3: Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the _README.md_ file included in your GitHub repository.

Structure your report by using the _report_template.md_ that _Starter_Code.zip_ included, ensuring that it contains the following:

1) __An Overview of the Analysis:__ Explain the purpose of this analysis.

2) __The Results:__ Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

3) __A Summary:__ Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.







## Resources
### Bootcamp References -- update later
Module 20 Instructions
 
starter_code folder
* credit_risk_classification.ipynb


Example Data:
* report-template.md


Resources
* lending_data.csv


 
***Special Thanks:***
* Jamie Miller
* Mounika Mamindla
* Lisa Shemanciik
 
### External References
_(where possible will provide link to website)_
* [pandas documentation](https://pandas.pydata.org/docs/reference/general_functions.html)
* [matplotlib documentation](https://matplotlib.org/stable/index.html)
* [hvplot documentation](https://hvplot.holoviz.org/reference/geopandas/points.html)
* [scipy.stats documentation](https://docs.scipy.org/doc/scipy/reference/stats.html)

