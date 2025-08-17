# Project 6: Customer Satisfaction Classification

## Context
This project aims to predict customer satisfaction based on flight and service data. Using a dataset with features related to in-flight services, delays, and booking experiences, we explore data preprocessing, encoding, scaling, and machine learning classification.

## Objective
- Clean and preprocess the dataset.
- Analyze correlations between features and customer satisfaction.
- Train multiple machine learning models to classify satisfied vs. unsatisfied customers.
- Evaluate models using metrics suitable for imbalanced datasets (Balanced Accuracy, Matthews Correlation Coefficient, F1-score).

## Data Sources
- CSV datasets for training and testing: `train.csv` and `test.csv`.

## Steps
1. Import libraries: pandas, numpy, matplotlib, seaborn, sklearn.
2. Load datasets and inspect columns.
3. Handle missing values, particularly in `Arrival Delay in Minutes`.
4. Encode categorical variables using OneHotEncoder and LabelEncoder.
5. Remove unnecessary columns and duplicates (`id`, `Unnamed: 0`).
6. Analyze correlations and outliers using boxplots and Z-scores.
7. Split data into features (`X_train`, `X_test`) and target (`y_train`, `y_test`).
8. Scale features using `MinMaxScaler`.
9. Train classification models:
    - Model 1: Voting classifier combining KNN, Decision Tree, and Logistic Regression (with GridSearchCV for hyperparameter tuning).
    - Model 2: Random Forest classifier (with GridSearchCV).
10. Evaluate models with classification reports and feature importance.
11. Interpret results to understand key drivers of customer satisfaction.

## Notebook
- `Customer_Satisfaction_Classification.ipynb`

## Notes
- All code comments are in **Italian**.
- Feature importance analysis highlights which service aspects most influence satisfaction (e.g., Online Boarding, Inflight WiFi Service).
- The notebook demonstrates full workflow from preprocessing to model evaluation.
