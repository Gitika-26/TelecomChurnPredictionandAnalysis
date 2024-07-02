# Telecom Churn Prediction and Analysis

This portfolio project includes the analysis and prediction of churn of telecom customers. It aims to predict customer churn for a subscription service using supervised machine learning techniques. Churn prediction helps businesses identify customers who are likely to cancel their subscription, allowing for proactive retention strategies. The insights and predictions are visualized using Power BI for better decision-making.

Table of Contents-
Introduction
Dataset
Data Preprocessing
Exploratory Data Analysis (EDA)
Machine Learning Models
Model Evaluation
Results
Installation and Usage
Contributing
License


Introduction
Customer churn is a critical issue for telecom companies as it directly impacts revenue and profitability. By predicting churn, businesses can implement targeted retention strategies to retain valuable customers. This project focuses on predicting customer churn using various machine learning models and visualizing the insights through Power BI.

Dataset
The dataset used in this project includes information on telecom customers and their subscription details. The columns are:

SeniorCitizen
tenure
customerID
gender
Partner
Dependents
PhoneService
MultipleLines
InternetService
OnlineSecurity
OnlineBackup
DeviceProtection
TechSupport
MonthlyCharges
StreamingTV
StreamingMovies
Contract
PaperlessBilling
PaymentMethod
TotalCharges
Churn


Data Preprocessing
To prepare the data for modeling, the following preprocessing steps were performed:
Handling missing values
Encoding categorical variables
Normalizing numerical features


Exploratory Data Analysis (EDA)
EDA was conducted to understand the distribution and relationships between variables. Key insights were visualized using various plots and graphs.

Machine Learning Models
The following machine learning models were implemented and evaluated:

Logistic Regression
Random Forest
Gradient Boosting
Support Vector Classification (SVC)
KNN Classification
Model Evaluation


The models were evaluated using the following metrics:

Accuracy
Precision
Recall
F1 Score

Results
The Gradient Boosting model provided the best performance with the following metrics:

Accuracy: 80.65%
Precision: 84 %
Recall: 91 %
F1 Score: 87 %

Detailed performance metrics for each model are provided in the results section of the project.






