 Titanic Survival Prediction using Linear Regression
 ---------Project Overview------------

This project predicts the survival outcome of Titanic passengers using Linear Regression, a fundamental machine learning algorithm. Although Linear Regression is primarily used for continuous values, it is applied here for educational purposes to understand regression-based prediction, feature relationships, and model evaluation in a real-world dataset.

---------Dataset Description-----------

Dataset Name: Titanic Dataset

Source: Kaggle (Public Dataset)

Download Link: https://hbiostat.org/data/repo/titanic3.xls

Format: Excel (.xls / .xlsx)

Number of Rows / Columns: Depends on dataset version

Features:

Pclass (Passenger class)

Sex

Age

SibSp (Siblings/Spouses aboard)

Parch (Parents/Children aboard)

Fare

Embarked (Port of embarkation)

Target Variable: Survived (0 = Not Survived, 1 = Survived)

Observation: Dataset includes numerical and categorical values requiring preprocessing before regression.

--------- Data Preprocessing----------

Handled missing values in Age, Fare, and Embarked

Removed irrelevant columns such as Name, Ticket, and Cabin

Converted categorical features (Sex, Embarked) into numerical values

Normalized numerical features for better regression performance

Split dataset into training and testing sets

---------Features and Target Definition----------

Features (X):
Pclass, Sex, Age, SibSp, Parch, Fare, Embarked

Target (y):
Survived

---------Model Training---------

Algorithm Used: Linear Regression

Libraries:
pandas, numpy, scikit-learn, matplotlib, seaborn

The model is trained using training data and generates continuous output values representing survival probability.

----------Evaluation Metrics----------

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score (Coefficient of Determination)

These metrics are used to evaluate regression performance.

--------- Actual vs Predicted----------

An Actual vs Predicted scatter plot is generated to visually compare real survival outcomes with model predictions, helping to analyze prediction accuracy and error distribution.

---------Pseudo Confusion Matrix----------

Since Linear Regression produces continuous values, predictions are converted into binary classes using a threshold (e.g., 0.5) to create a pseudo confusion matrix for interpretability.

-------- GitHub Repository---------

Dataset file: titanic3.xls

Jupyter Notebook / Python script for data preprocessing, training, and evaluation

Clear and commented code for beginners

-------Instructions to Run-------

Download the Titanic dataset from the provided link.

Load the dataset using Pandas.

Perform data preprocessing and feature encoding.

Train the Linear Regression model.

Evaluate predictions using regression metrics and visualization.

-------Conclusion---------

This project demonstrates the application of Linear Regression to a classification-style problem for learning purposes. While Logistic Regression is more suitable for survival prediction, Linear Regression helps in understanding feature impact, prediction errors, and regression evaluation techniques.

 -------Author--------

Name: Shoaib Malik
Email: shoaibdesignpoint13@gmail.com
