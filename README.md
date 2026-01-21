Loan Approval Analysis and Prediction using Financial Risk Indicators
Project Overview

This project analyzes loan application data to understand the factors influencing loan approval decisions and builds a machine learning model to predict loan approval outcomes.
Exploratory Data Analysis (EDA) is performed to identify key financial risk indicators such as CIBIL score, income, assets, loan amount, loan term, and EMI burden.
The project aims to support better credit decision-making by combining statistical insights with predictive modeling.

Objectives

Analyze applicant financial and personal attributes affecting loan approval
Perform Exploratory Data Analysis to identify approval patterns
Create financial risk metrics such as EMI-to-Income ratio
Build and evaluate a classification model for loan approval prediction
Provide business insights for credit risk assessment

Dataset
The dataset contains applicant details including:
1. CIBIL Score
2. Annual Income
3. Loan Amount
4. Loan Term
5. Employment Status
6. Dependents
7. Asset Ownership
8. Loan Status (Approved / Rejected)

Exploratory Data Analysis

Key analyses performed:
1. Target variable distribution (Approved vs Rejected)
2. CIBIL score buckets and approval rates
3. Income vs Loan Amount analysis
4. Asset ownership impact on approval
5. Employment and education impact
6. EMI-to-Income ratio analysis
7. Correlation heatmap

Machine Learning Model

Algorithm used: Logistic Regression

1. Train-test split applied
2. Model evaluation using:
    A. Accuracy
    B.Classification Report
    C.Confusion Matrix

Key Insights

1. CIBIL score is the strongest factor influencing loan approval.
2. Income and loan amount show high overlap between approved and rejected cases.
3. Asset ownership and loan term have moderate impact
4. EMI-to-Income ratio provides useful repayment risk indication

Tools & Technologies

1. Python
2. Pandas, NumPy
3. Matplotlib, Seaborn
4. Scikit-learn
5. Jupyter Notebook

Conclusion

The project demonstrates how financial risk indicators and applicant attributes influence loan approval decisions and shows how machine learning can assist in automating credit risk assessment.
