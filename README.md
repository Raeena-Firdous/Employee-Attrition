# EMPLOYEE ATTRITION PREDICTION USING MACHINE LEARNING

## 1)Employee Attrition EDA:

### DATA

The dataset we use is publicly available and can be accessed from [here](https://excelbianalytics.com/wp/downloads-21-sample-csv-files-data-sets-for-testing-till-5-million-records-hr-analytics-for-attrition/).

The dataset has (1000000R X 35C) that contains numeric and categorical data types describing each employee’s background and characteristics; and labelled (supervised learning) with whether they are still in the company or whether they have gone to work somewhere else. Machine Learning models can help to understand and determine how these factors relate to workforce attrition.
 
* checking for the null values.
* checking for the duplicate values.
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis


## 2)Employee Attrition Preprocessing:
* Checking for outliers
* Data Cleaning
* Pearson Correlation
* One-Hot Encoding
* Feature Scaling(Normalization)

## 3)Employee Attrition feature selection:

#### Initial model building using evalML without feature selection
### Feature Selection
##### feature importance using random forest classifier (Selected top 21 features):
comment: after feature importance applied some algorithms and we were getting 50% accuracy.
##### feature selection using SelectKBest (Selected top 15 features):
comment: after SelectKBest feature selection applied some algorithms and we were getting 50% accuracy.

## 4)Employee Attrition Model-1:

comment: after performing feature selection most of the models encountered with the lower accuracy of 50% , so we decided to keep all the features for model building.
### Model Building
we have trained and tested various machine learning classification models.

[here](https://github.com/Raeena-Firdous/Employee-Attrition/blob/main/4)Employee%20Attrition%20Model-1.ipynb)

## 5)Employee Attrition Model-2:

As we were getting less accuracy from the model-1. so we have created this model-2 by creating a new column "attrition_within_a_year" using YearAtCompany column¶
to see whether an employee get attritioned with in a year or not.we made this "attrition_within_a_year" feature as our dependent variable and we dropped the attrition column from our dataset. 
Initially it was in imbalanced form. so for handling that we used a oversampling technique(SMOTE).
### Model Building
we have trained and tested various machine learning classification models.

(https://github.com/Raeena-Firdous/Employee-Attrition/blob/main/5)Employee%20Attrition%20Model-2.ipynb)

