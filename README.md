# Fetal Health Classification

This project focuses on classifying fetal health status using structured medical data and machine learning techniques.
The task is formulated as a multi-class classification problem.

## Problem Statement
Accurate assessment of fetal health is critical in prenatal care.
The goal of this project is to build a machine learning model that classifies fetal health conditions into clinically meaningful categories.

## Dataset
The dataset contains cardiotocography (CTG) features with the target variable:
- 1: Normal
- 2: Suspect
- 3: Pathological

All features are numerical and no missing values are present.

## Approach
- Data loading and basic validation
- Feature and label separation
- Train-test split with stratification
- Feature scaling
- Model training and comparison

## Models Used
- Logistic Regression (baseline, interpretable)
- Random Forest (non-linear model for improved performance)

## Evaluation
Models are evaluated using standard multi-class classification metrics such as precision, recall, and F1-score.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn

## Key Learnings
- Handling structured medical datasets
- Building multi-class classification pipelines
- Comparing baseline and ensemble models
- Applying proper data splitting and scaling techniques

## Future Improvements
- Hyperparameter tuning
- Feature importance analysis
- Model deployment as an API
