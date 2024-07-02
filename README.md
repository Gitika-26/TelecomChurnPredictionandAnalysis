# Telecom Churn Prediction and Analysis

This portfolio project includes the analysis and prediction of churn of telecom customers. It aims to predict customer churn for a subscription service using supervised machine learning techniques. Churn prediction helps businesses identify customers who are likely to cancel their subscription, allowing for proactive retention strategies. The insights and predictions are visualized using Power BI for better decision-making.

## Table of Contents-
[Introduction](#intro)  <br>
[Dataset](#dataset) <br>
[Data Preprocessing](#datapreprocessing)  <br>
[Exploratory Data Analysis (EDA)](#EDA)  <br>
[Machine Learning Models](#MLModels)  <br>
[Model Evaluation](#ModelEvaluation)  <br>
[Results](#Results) <br>


<a name="intro"></a>
## Introduction
Customer churn is a critical issue for telecom companies as it directly impacts revenue and profitability. By predicting churn, businesses can implement targeted retention strategies to retain valuable customers. This project focuses on predicting customer churn using various machine learning models and visualizing the insights through Power BI. <br>

<a name="dataset"></a>
## Dataset
The dataset used in this project includes information on telecom customers and their subscription details. The columns are:  <br>
* SeniorCitizen  <br>
* tenure  <br>
* customerID  <br>
* gender  <br>
* Partner  <br>
* Dependents  <br>
* PhoneService  <br>
* MultipleLines  <br>
* InternetService  <br>
* OnlineSecurity  <br>
* OnlineBackup  <br>
* DeviceProtection  <br>
* TechSupport  <br>
* MonthlyCharges  <br>
* StreamingTV  <br>
* StreamingMovies  <br>
* Contract  <br>
* PaperlessBilling  <br>
* PaymentMethod  <br>
* TotalCharges  <br>
* Churn  <br>

<a name="datapreprocessing"></a>
## Data Preprocessing
To prepare the data for modeling, the following preprocessing steps were performed:  <br>
* Handling missing values  <br>
* Encoding categorical variables  <br>
* Normalizing numerical features <br>

<a name="EDA"></a>
## Exploratory Data Analysis (EDA)
EDA was conducted to understand the distribution and relationships between variables. Key insights were visualized using various plots and graphs.

<a name="MLModels"></a>
## Machine Learning Models
The following machine learning models were implemented and evaluated:  <br>
* Logistic Regression  <br>
* Random Forest  <br>
* Gradient Boosting  <br>
* Support Vector Classification (SVC)  <br>
* KNN Classification  <br>

<a name="ModelEvaluation"></a>
## Model Evaluation
The models were evaluated using the following metrics:  <br>
* Accuracy  <br>
* Precision  <br>
* Recall  <br>
* F1 Score  <br>


<a name="Results"></a>
## Results
The Gradient Boosting model provided the best performance with the following metrics:  <br>
* Accuracy: 80.65%  <br>
* Precision: 84 %  <br>
* Recall: 91 %  <br>
* F1 Score: 87 %  <br>








