# Loan-Status-Prediction-Using-Machine-Learning
# Classification Loan Status


# Introduction:
we are going to work on binary classification problem, where we got some information about sample of peoples , and we need to predict whether we should give some one a loan or not depending on his information . we actually have a few sample size (614 rows), so we will go with machine learning techniques to solve our problem .
# About the data
Loan_ID : Unique Loan ID

Gender : Male/ Female

Married : Applicant married (Y/N)

Dependents : Number of dependents

Education : Applicant Education (Graduate/ Under Graduate)

Self_Employed : Self employed (Y/N)

ApplicantIncome : Applicant income

CoapplicantIncome : Coapplicant income

LoanAmount : Loan amount in thousands of dollars

Loan_Amount_Term : Term of loan in months

Credit_History : Credit history meets guidelines yes or no

Property_Area : Urban/ Semi Urban/ Rural

Loan_Status : Loan approved (Y/N) this is the target variable

# what you will learn in this kernel ?

basics of visualizing the data .

# how to compare between feature importance (at less in this data) .

feature selection

feature engineer

# some simple techniques to process the data .

handling missing data .

how to deal with categorical and numerical data .

outliers data detection

but the most important thing that you will learn , is how to evaluate your model at every step you take .

# what we will use ?
some important libraries like sklearn, matplotlib, numpy, pandas, seaborn, scipy

fill the values using backward 'bfill' method for numerical columns , and most frequent value for categorical columns (simple techniques)

## 4 different models to train your data, so we can compare between them
1.Logistics Regression

2.Support Vector Classifiers (SVC)

3.Decision Tree Classifier

4.Random Forest Classifier

5.Gradient Boosting Classifier

To predict the accuracy we will use the accuracy score function from scikit-learn library.
