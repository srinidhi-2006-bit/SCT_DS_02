# SCT_DS_02

# Titanic Survival Prediction using Machine Learning
## Project Objective
   To build a classification model that predicts whether a passenger survived the Titanic disaster based on features like age, gender, ticket class, etc. The goal is to explore data preprocessing, feature engineering, and machine learning modeling.

## Dataset Information
   - Dataset File: train.csv (from Kaggle Titanic Competition)
- Attributes:
  - Pclass, Sex, Age, Fare, Embarked, SibSp, Parch, Survived (target)

## Steps Followed
1. Data Loading & Exploration
   - Loaded data with pandas
   - Used info() and describe() for quick overview
2. Data Cleaning
   - Filled missing values in Age with median
   - Filled missing values in Embarked with mode
   - Dropped columns like Cabin, Ticket, Name
3. Feature Engineering
   - Converted categorical features (Sex, Embarked) into numeric with LabelEncoder
   - Combined SibSp and Parch into FamilySize
4. Model Training
   - Split data into training and testing sets
   - Trained models using Logistic Regression, Random Forest, and KNeighborsClassifier
5. Evaluation
   - Compared accuracy and confusion matrix
   - Selected the best-performing model

## Model Accuracy

| Model              | Accuracy |
|-------------------|----------|
| LogisticRegression| ~79%     |
| RandomForest      | ~81%     |
| KNN               | ~77%     |

## Files Included
   - train.csv
   - Titanic_Survival_Prediction.ipynb
   - README.md

## Author Notes
   This project was a great hands-on exercise in preparing messy real-world data, applying ML models, and interpreting results. I learned the importance of handling missing values and feature engineering.
