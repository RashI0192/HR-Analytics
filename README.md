# HR-Analytics
( check comments in the codes (Loading And Combining Dataset-> One Hot Encoding -> EDA for Attrition Rate -> EDA on Performance Insights) for detailed explanation )
### Problem Statement
I created a machine learning model to assist HR departments in hiring the best candidates by identifying the characteristics of successful, long-term employees. The model will not only predict the likelihood of attrition but also suggest the traits that lead to employee success and longevity, enabling HR teams to hire candidates who are more likely to succeed and stay with the company

### Key Objectives:

- Identify features that make employees more likely to stay long-term (e.g., role, experience, education) depending on their department (Sales, R&D, HR)
- Predict which candidates are likely to be a good cultural and professional fit based on historical data.
- Recommend improvements to the hiring process that align with company goals and workforce needs and reduce attrition rates in the selected departments. [check EDA for Attrition Rate ] 


<img width="1311" alt="Screenshot 2025-01-10 at 9 20 17 PM" src="https://github.com/user-attachments/assets/5ea92fb6-1c9e-4b1a-b0d9-60e74dac113b" />

### 2 Models : 
- Top 5 Correlated Features and other domain specific features extracted to reduce overfitting
- Practiced thorough EDA, feature engineering and cross validation to avoid overfitting
##### Model 1:
- 85% accuracy
- to help HR departments analyze employee data and predict performance ratings, aiding in candidate selection and workforce plannin
- hyperparameters tuning using RandomizedSearchCV and model trained on Gradient Boost

#### Model 2: 
- 93% Accuracy (Logistic Regression Performance),90%(Naive Bayes),88.65%(RandomForest)
- Goal is to predict the Attrtion Rate
- <img width="524" alt="Screenshot 2025-01-10 at 9 32 15 PM" src="https://github.com/user-attachments/assets/aa6a78dc-0922-481c-8a39-465d7e3ce79c" />

# SHAP Explanation
- Since this model is designed to assist HR professionals, transparency is critical to ensure a clear understanding of how predictions are made. This enhances trust and enables HR teams to interpret the model's outcomes effectively for better decision-making.

<img width="759" alt="Screenshot 2025-01-10 at 9 34 12 PM" src="https://github.com/user-attachments/assets/b7e41fd1-b78d-42ce-aaeb-94688a92425d" />

