# Titanic Survival Prediction Project

## Project Overview
This project is a classic data science classification problem. The goal is to predict whether a passenger on the Titanic survived or not based on a set of features like their age, class, sex, etc. This project demonstrates a complete data science workflow from data cleaning and exploratory analysis to feature engineering and model evaluation.

## Data Science Workflow
1.  **Exploratory Data Analysis (EDA):** Investigated the dataset to understand variable distributions, find correlations, and form hypotheses.
2.  **Data Cleaning:** Handled missing values using informed strategies (e.g., imputing missing `Age` based on passenger class and gender).
3.  **Feature Engineering:** Created new features to improve model performance, including `FamilySize`, `IsAlone`, and `Title` (extracted from names).
4.  **Modeling:** Trained a `RandomForestClassifier` on the processed data.
5.  **Evaluation:** Assessed the model using Accuracy, a Confusion Matrix, Precision, Recall, F1-Score, and the ROC/AUC score.

## Key Results
* The model achieved an accuracy of **84.92%** and an AUC score of **90.2**.
* The most important features for predicting survival were found to be gender, passenger class, fare, and age.

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
