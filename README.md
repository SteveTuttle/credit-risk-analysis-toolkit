# credit-risk-analysis-toolkit
UNC_data_bootcamp_module_20

## Challenge Description
### Background
> For this Challenge, we are going to use various techniques to train and evaluate a model based on loan risk. We will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

***from the UNC Bootcamp instructions for this challenge***

## Deliverables
This challenge is broken down into three subsections:
* Split the Data into Training and Testing Sets
* Create a Logistic Regression Model with the Original Data
* Write a Credit Risk Analysis Report

    * Outside of the primary deliverable for this challenge which called the for the creation a Logistic Regression model, the Credit Risk Analysis Report asks to see and compare two models. I am adding a Random Forest for comparison in the notebook as well.

### Part-1: Split the Data into Training and Testing Sets
Getting started, I will open the notebook from the starter code __`credit_risk_classification.ipynb`__ then save a new copy as __`credit_risk_classification_sdt.ipynb`__ and that will be the file I use to complete the following steps per challenge instructions:

1) Read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame.

2) Create the _labels_ set (`y`) from the “loan_status” column, and then create the _features_ (`X`) DataFrame from the remaining columns.

      * __NOTE:__ A value of __0__ in the “loan_status” column means that the loan is healthy. A value of __1__ means that the loan has a high risk of defaulting.

3) Split the data into training and testing datasets by using `train_test_split`.


### Part-2: Create a Logistic Regression Model with the Original Data
For the part of the challenge, I will use what I've about logistic regression models to complete the following steps the challenge instructions and the notebook code:

1) Fit a logistic regression model by using the training data (`X_train` and `y_train`).

2) Save the predictions for the testing data labels by using the testing feature data (`X_test`) and the fitted model.

3) Evaluate the model’s performance by doing the following:
      * Generate a confusion matrix.
      * Print the classification report.

4) Answer the following question: How well does the logistic regression model predict both the __0__ (healthy loan) and __1__ (high-risk loan) labels?

_Confusion Matrix Display_

![Confusion Matrix Display](https://github.com/SteveTuttle/credit-risk-classification/blob/main/Output/cm_display.png)

### Part-3: Write a Credit Risk Analysis Report
Lastly, the instructions require that I will write a credit risk analysis report which includes a summary and analysis of the performance of the machine learning models used in this challenge. This report will be written in as a _README.md_ file included with this challenge GitHub repository. The `report_template.md` calls for the results of two models and a comparison between them, the model from the challenge (_Logistic Regression_) will be __Model 1__. For __Model 2__ I will add a Random Forest model to the `credit_risk_classification_sdt.ipynb` notebook solely for the comparison. I will structure the report using the `report_template.md` that the original `Starter_Code.zip` included, while ensuring that it contains the following:

1) __An Overview of the Analysis:__ Explain the purpose of this analysis.

2) __The Results:__ Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

3) __A Summary:__ Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

_Click the link below  to view the final report_:

[Credit Risk Analysis Report](https://github.com/SteveTuttle/credit-risk-classification/blob/main/Output/credit_risk_analysis_report.md)


## Resources
### Bootcamp References
[Module 20 Instructions](https://courses.bootcampspot.com/courses/3285/assignments/52247?module_item_id=937508)

Module 20 Class Activities

Starter_Sode folder
* credit_risk_classification.ipynb

_report example_:
* report-template.md

Resources
* lending_data.csv


***Special Thanks:***
* Jamie Miller
* Mounika Mamindla
* Lisa Shemanciik

### External References
* [pandas documentation](https://pandas.pydata.org/docs/reference/general_functions.html)
* [matplotlib documentation](https://matplotlib.org/stable/index.html)
* [scikit-learn documentation](https://scikit-learn.org/stable/user_guide.html)
* [Google](https://www.google.com)
* [YouTube](https://www.youtube.com)

