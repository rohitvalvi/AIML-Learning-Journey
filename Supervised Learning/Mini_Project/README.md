Loan Approval Prediction System
This project implements machine learning models to automate the eligibility process for loan applicants. Using historical data, the system predicts whether a loan application will be approved based on financial, demographic, and credit-related features.

 Dataset Overview (loan_approval_data.csv)
The dataset consists of 1,000 records and 20 features. It contains diverse information about applicants, including:
Target Variable: Loan_Approved (Yes/No).
Financial Data: Applicant_Income, Coapplicant_Income, DTI_Ratio (Debt-to-Income), Savings, and Collateral_Value.
Credit Information: Credit_Score and Existing_Loans.
Demographics: Age, Gender, Marital_Status, Dependents, and Education_Level.
Loan Details: Loan_Amount, Loan_Term, and Loan_Purpose.

 Workflow in the Notebook (Loan_Approval.ipynb)
The analysis follows a standard data science pipeline:
Data Cleaning:
Missing numerical values are imputed using the Mean strategy.
Missing categorical values are imputed using the Most Frequent strategy.
Exploratory Data Analysis (EDA):
The project explores class distribution (Approved vs. Not Approved).
Demographic analysis, such as gender distribution (621 Male vs. 379 Female applicants).
Preprocessing: Features are scaled and categorical variables are encoded to prepare for model training.

 Machine Learning Models
Several classification algorithms are implemented and evaluated, including:
Logistic Regression
K-Nearest Neighbors (KNN)
Gaussian Naive Bayes.

Model Performance Example (Naive Bayes):
Accuracy: 86%.
Precision: 0.811.
Recall: 0.705.
F1 Score: 0.754.

 Requirements
To run the notebook, ensure you have the following Python libraries installed:
pandas
numpy
seaborn
matplotlib
scikit-learn.
