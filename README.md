#Telco Customer Churn Prediction
##Overview
This project focuses on predicting customer churn for a telecommunications company using machine learning techniques. The dataset contains customer information, including demographics, account details, and service usage, with the target variable indicating whether a customer has churned (left the service).

##Dataset
The dataset used is WA_Fn-UseC_-Telco-Customer-Churn.csv, which includes 7043 entries with 21 features. Key features include:

Demographics: gender, senior citizen status, partner/dependents

Account information: tenure, contract type, payment method

Services: phone service, internet service, online security, etc.

Charges: monthly and total charges

Target: Churn (Yes/No)

##Data Preprocessing
Handling Missing Values: Converted 'TotalCharges' to numeric and filled missing values with 0.

Encoding Categorical Variables: Used LabelEncoder to convert categorical features to numerical values.

Feature Scaling: Applied StandardScaler to numerical features ('tenure', 'MonthlyCharges', 'TotalCharges').

Train-Test Split: Divided the data into 80% training and 20% testing sets.

##Exploratory Data Analysis (EDA)
Visualized the distribution of the target variable 'Churn'.

Analyzed feature correlations and distributions.

##Models Implemented
The notebook includes implementations of the following machine learning models:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

##Evaluation Metrics
Models are evaluated using:

##Accuracy

Classification Report (precision, recall, f1-score)

##Requirements
Python 3.x

##Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

TensorFlow/Keras

##How to Run
Clone the repository.

Install the required libraries 

Run the Jupyter notebook Final_Project_(1).ipynb.

##Results
The best-performing model achieved an accuracy of [insert accuracy here]. Detailed performance metrics for each model can be found in the notebook.

##Future Work
Hyperparameter tuning for better performance.

Feature engineering to improve model accuracy.

Deployment of the best model as a web application.
