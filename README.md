# EMPLOYEE ATTRITION PREDICTION USING MACHINE LEARNING

## 1)Employee Attrition EDA:

### DATA
The dataset we use is publicly available.The dataset has (1000000R X 35C) that contains numeric and categorical data types describing each employee’s background and characteristics; and labelled (supervised learning) with whether they are still in the company or whether they have gone to work somewhere else. Machine Learning models can help to understand and determine how these factors relate to workforce attrition.

This dataset consist of 1000000 rows and 35 columns.The description about each attribute is:¶
* BusinessTravel - Business travel is travel undertaken for work or business purposes.
* DailyRate - the prescribed amount of pay for a given job of work paid for by the day or hour.
* Department - It shows to which department an employee belongs to.
* Education - It specifies number of years of education completed.
* EducationField - It shows to which education field an employee belongs to.
* EnvironmentSatisfaction - Numerical Value - satisfaction with the environment.
* HourlyRate - it shows hourly salary.
* JobInvolvement - A person who has a high level of job involvement usually obtains major life satisfaction from the job (1 means High -4 means Low).
* JobLevel - categories with different titles and salary ranges within a workplace (1 means High - 4 means Low).
* JobRole - It simply defines the job position.
* JobSatisfaction - A feeling of fulfilment or enjoyment that a employee derives from their job (1 means High - 4 means Low).
* MonthlyIncome - Amount paid to an employee within a month.
* MonthlyRate - The internal charge out rate which will be used to calculate the cost of each employee monthly, in general, the monthly rate will cover salary, social insurance, administration, logistics, over head etc.
* MonthlyIncome - Monthly income is just how much the employee earned monthly.
* NumCompaniesWorked - Number of companies an employee worked or experience an employee had.
* OverTime - it simply defines an over time work done by an employee.
* PercentSalaryHike - (New salary - Old salary) * 100 / (Old salary).
* PerformanceRating - It observes the worker's performance and records a value (1 means High - 4 means Low).
* StockOptionLevel - It is issued by the company for its employees to encourage employee ownership in the company. The shares of the companies are given to the employees at discounted rates.

#### checking for the null values.
#### checking for the duplicate values.
#### Univariate Analysis
#### Bivariate Analysis
#### Multivariate Analysis


## 2)Employee Attrition Preprocessing:

### Checking for outliers
### Data Cleaning
### Pearson Correlation
### One-Hot Encoding
### Feature Scaling(Normalization)

## 3)Employee Attrition feature selection:

### Initial model building using evalML without feature selection
### Feature Selection
#### feature importance using random forest classifier (Selected top 21 features):
comment: after feature importance applied some algorithms and we were getting 50% accuracy.
#### feature selection using SelectKBest (Selected top 15 features):
comment: after SelectKBest feature selection applied some algorithms and we were getting 50% accuracy.

## 4)Employee Attrition Model-1:

comment: after performing feature selection most of the models encountered with the lower accuracy of 50% , so we decided to keep all the features for model building.
### Model Building
we have trained and tested various machine learning classification models.

#### [Employee Attrition Model-1] 
(https://github.com/Raeena-Firdous/Employee-Attrition/blob/main/4)Employee%20Attrition%20Model-1.ipynb)


