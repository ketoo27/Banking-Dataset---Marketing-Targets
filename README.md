Banking Dataset - Marketing Targets
Project Overview
This project involves building a machine learning model to identify potential marketing targets for a bank based on customer data. The goal is to predict whether a customer will respond positively to a marketing campaign.

Objectives
Develop a machine learning model to predict customer response to a marketing campaign.
Identify potential marketing targets based on the model's predictions.
Key Highlights
Model Used: Random Forest Classifier
Accuracy: 90%
Challenges Overcome:
Addressed data imbalance using Tomek Links undersampling.
Engineered the age_balance_ratio feature to improve model performance.
Preprocessed categorical and numerical features effectively.
Steps and Methodology
Problem Definition:

Objective: Predict customer response to marketing campaigns and identify potential marketing targets.
Data Preprocessing:

Encoded categorical variables using LabelEncoder.
Scaled numerical features using StandardScaler.
Created a new feature, age_balance_ratio, to capture the relationship between age and balance.
Handling Imbalanced Data:

Applied Tomek Links undersampling to balance the dataset and improve model performance.
Model Training:

Trained a Random Forest Classifier with a fixed random state for reproducibility.
Model Evaluation:

Evaluated the model using metrics such as precision, recall, F1-score, and accuracy.
Plotted the ROC curve and calculated the AUC to assess the model's performance.
Prediction:

Implemented functions to preprocess user input and predict the probability of a customer converting into a customer.
Installation
