# TelecomChurnPredictionandAnalysis
This portfolio project include analysis and prediction of churn of telecom customers
This project aims to predict customer churn for a subscription service using supervised machine learning techniques Churn prediction helps businesses identify customers who are likely to cancel their subscription, allowing for proactive retention strategies. The insights and predictions are visualized using Power BI for better decision-making.


Data The dataset used in this project includes the following information: Customer demographics Subscription details Usage data Support tickets The columns are ['SeniorCitizen', 'tenure' 'customerID', 'gender', 'Partner', 'Dependents', 'PhoneService', 'MultipleLines', 'InternetService', 'OnlineSecurity', 'OnlineBackup', 'DeviceProtection', 'TechSupport', 'MonthlyCharges','StreamingTV', 'StreamingMovies', 'Contract', 'PaperlessBilling', 'PaymentMethod', 'TotalCharges', 'Churn']

The dataset has to be preprocessed to handle missing values, encode categorical variables, and normalize numerical features.

The following machine learning models were implemented and evaluated:

Logistic Regression,
Random Forest,
Gradient Boosting,
Support Vector Classification,
KNN Classification

Model Evaluation The models were evaluated using the following metrics:

Accuracy Precision Recall F1 Score ROC-AUC

Results The Gradient Boosting model provided the best performance with an accuracy of X%, precision of Y%, and recall of Z%. Feature importance analysis showed that Monthly Charges, Subscription Duration, and Number of Support Tickets were the top predictors of churn.

Power BI Dashboard The Power BI dashboard provides the following insights:

Churn Probability by Customer Segment Feature Importance Analysis Churn Rate Trends Comparison of Churned vs. Retained Customers

Installation To run this project locally, follow these steps:

Clone the repository:

bash Copy code git clone https://github.com/Gitika-26/TelecomChurnPredictionandAnalysis.git Navigate to the project directory:

bash Copy code cd customer-churn-prediction Create a virtual environment:

bash Copy code python -m venv venv Activate the virtual environment:

bash Copy code

On Windows
venv\Scripts\activate

On macOS/Linux
source venv/bin/activate Install the required dependencies:

bash Copy code pip install -r requirements.txt Run the Jupyter Notebook:

bash Copy code jupyter notebook Usage Open customer_churn_prediction.ipynb in Jupyter Notebook. Follow the steps in the notebook to preprocess the data, train the models, and evaluate their performance. Export the predictions and insights for visualization in Power BI. Contributing Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
