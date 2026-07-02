# loan-approval-prediction
Machine Learning project for predicting loan approval status using Support Vector Machine (SVM) with data preprocessing, exploratory data analysis, and model evaluation.

<p align="center">
  <img src="banner.png" width="900"/>
</p>

🔍 Project Overview  
This project focuses on building a machine learning model that predicts whether a loan application will be approved or rejected based on applicant financial and demographic information such as income, education, credit history, property area, and more. The goal is to assist in automating the loan approval process using data-driven decision making.

🎯 Objectives  

Predict loan approval status (Approved / Rejected).  
Understand key factors influencing loan decisions.  
Build a classification model using Support Vector Machine (SVM).  
Evaluate model performance using standard classification metrics.

📂 Dataset  
Source: Kaggle Loan Prediction Dataset (https://www.kaggle.com/datasets/ninzaami/loan-predication)  
The dataset contains 614 records and 13 features including applicant income, loan amount, credit history, and property area. The target variable is Loan_Status, which indicates whether the loan was approved or not.

🛠️ Data Preprocessing  
The dataset contained missing values and categorical variables which were handled during preprocessing. Missing values were treated appropriately, categorical variables were converted into numerical format using label encoding, and irrelevant features such as Loan_ID were removed. Inconsistent values like “3+” in Dependents were also cleaned to ensure data quality before training.

📊 Exploratory Data Analysis  
The data was analyzed to understand relationships between different features and loan approval status. It was observed that credit history has a strong influence on loan approval outcomes, while factors like education, marital status, and property area also show moderate impact.

🤖 Machine Learning Model  
A Support Vector Machine (SVM) classifier was used for training the model. The dataset was split into training and testing sets, and the model learned patterns from the processed data to classify loan applications.

📈 Model Evaluation  
The model was evaluated using accuracy, precision, recall, F1-score, classification report, and confusion matrix to measure its performance on unseen data.

💡 Key Insights  
Credit history emerged as the most important factor influencing loan approval. Applicants with a positive credit history had a significantly higher approval rate. Proper data preprocessing improved model performance and ensured better generalization.

🧠 Conclusion  
This project demonstrates how machine learning can be applied to financial decision-making by predicting loan approval outcomes. The SVM model provides a strong baseline system that can be further improved using advanced models and feature engineering techniques.