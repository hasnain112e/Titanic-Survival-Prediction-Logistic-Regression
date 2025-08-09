# Titanic-Survival-Prediction-Logistic-Regression
A machine learning project that predicts Titanic passenger survival using Logistic Regression. This repository covers data cleaning, feature encoding, model training, and performance evaluation using accuracy, classification report, and confusion matrix visualization. Built with Python, Pandas, Seaborn, Matplotlib, and Scikit-learn.
# Titanic Survival Prediction - Logistic Regression

## Project Overview
This project predicts passenger survival on the Titanic using a Logistic Regression model. It involves data preprocessing, encoding categorical variables, training the model, and evaluating its performance with accuracy, precision, recall, and confusion matrix.

## Dataset
- Source: Seaborn's built-in Titanic dataset (`sns.load_dataset('titanic')`)
- Features include:
  - pclass: Passenger class (1, 2, 3)
  - sex: Gender (encoded: male=0, female=1)
  - age: Passenger age
  - sibsp: Number of siblings/spouses aboard
  - parch: Number of parents/children aboard
  - fare: Ticket fare
  - embarked: Port of embarkation (encoded: S=0, C=1, Q=2)

## Skills Covered
- Data Cleaning and Preprocessing
- Encoding Categorical Variables
- Logistic Regression (Binary Classification)
- Model Evaluation: Accuracy, Classification Report, Confusion Matrix

## Steps
1. Install dependencies:
   ```bash
   pip install pandas seaborn scikit-learn matplotlib
