# ==============================================================
#                       TITANIC SURVIVAL PREDICTION
#                   Machine Learning Project
# Author: Shoaib Malik
# Email: shoaibdesignpoint13@gmail.com


# ------------------  PROJECT OVERVIEW ------------------
# This project predicts whether a Titanic passenger survived or not.
# Beginner-friendly project to learn basic machine learning concepts:
# - Data cleaning
# - Feature selection
# - Making predictions
# - Checking accuracy with confusion matrix

# ------------------  DATASET INFORMATION ------------------
# Name: Titanic Dataset
# Format: Excel (.xls / .xlsx)
# Source: Public
# Download Link: https://hbiostat.org/data/repo/titanic3.xls

# ------------------  DATASET COLUMNS ------------------
# pclass    -> Passenger class (1st, 2nd, 3rd)
# survived  -> Did the passenger survive? (0 = No, 1 = Yes)
# name      -> Passenger name
# sex       -> Male or Female
# age       -> Age of passenger
# sibsp     -> Number of siblings/spouses onboard
# parch     -> Number of parents/children onboard
# fare      -> Ticket price
# embarked  -> Port where passenger boarded

# ------------------  PROJECT GOALS ------------------
# - Predict passenger survival
# - Compare predicted vs actual results
# - Build a confusion matrix
# - Measure model accuracy

# ------------------  ML CONCEPTS USED ------------------
# - Data cleaning & preprocessing
# - Feature selection
# - Train/test split
# - Classification (Logistic Regression)
# - Predictions vs actual comparison
# - Confusion matrix and accuracy score

# ------------------  MODEL EVALUATION ------------------
# Confusion matrix example:
# Actual \ Predicted | Not Survived | Survived
# -------------------|-------------|----------
# Not Survived       | TN          | FP
# Survived           | FN          | TP
# Accuracy, precision, recall, F1-score can also be used

# ------------------  TOOLS & LIBRARIES ------------------
# - Python
# - Pandas & NumPy
# - Scikit-learn
# - Matplotlib / Seaborn
# - Excel

# ------------------  HOW TO RUN ------------------
# 1. Download the Titanic dataset
# 2. Load it using Pandas
# 3. Clean and preprocess the data
# 4. Train a classification model
# 5. Predict survival outcomes
# 6. Check results with confusion matrix and accuracy

# ------------------  LICENSE ------------------
# This project is for educational purposes only.
# Dataset is publicly available and free to use
