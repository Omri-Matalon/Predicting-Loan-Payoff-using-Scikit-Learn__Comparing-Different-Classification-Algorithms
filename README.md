

# Predicting Loan Payoff vs. Collection using Scikit-Learn: Comparing Different Classification Algorithms

## Introduction
In this project, costumer loan payoff was predicted using the following classification algorithms: 

- k-nearest neighbors (KNN)
- Decision Trees
- Support-vector machine (SVM)
- Logistic Regression

To train and evaluate the accuracy of the classification algorithms, a dataset of past loans was used, which include details of 346 customers whose loan were already paid off or defaulted. The performance of the different classifiers was then evaluated on a test set and their accuracy results were summarized and compared. The data set includes the following fields: 


- **Loan_status**:	 Whether a loan is paid off or in collection
- **Principal**:  	 Basic principal loan amount at the
- **Terms**: 	 	     Weekly (7 days), biweekly, and monthly payoff schedule
- **Effective_date**:  When the loan got originated and took effects
- **Due_date**: 	     Payoff due date
- **Age**: 		     Age of applicant
- **Education**: 	     Education of applicant
- **Gender**:	         The gender of applicant




## Table of contents: 
1. Loading and examining the train data-set
2. Exploring the data using categorical and Pearson's correlations
3. Data visualization of specific variable combinations
4. Pre-processing: Feature selection / extraction
5. Classification
6. Model Evaluation using Test set
7. Models' Evaluation Report
