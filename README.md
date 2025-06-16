# Predicting House Prices Using Machine Learning and Feature Engineering

Housing prices vary due to many factors like location, size, number of rooms, and more. The goal of this project is to build a machine learning model that accurately predicts house prices based on various features in a structured dataset.This can help real estate professionals make better decisions.help them in investment planning and risk mitigation.

This project served as my introduction to building real-world data science pipelines and applying ML in a domain with significant financial impact.

📊 Dataset : Kaggle Dubai Properties - Apartments

🚧 Methodology :
1. Exploratory Data Analysis (EDA)

Visualized distributions and feature relationships

Handled missing values

Identified and removed outliers using IQR method

2. Feature Engineering

Applied SelectKBest to reduce dimensionality

Created polynomial features to capture non-linear relationships

3. Preprocessing

Label encoding and one-hot encoding for categorical variables

Normalization for numeric columns

4. Modeling

Used Scikit-learn Pipeline to combine preprocessing and model training

Models tested: Linear Regression, Polynomial Regression, Random Forest Regressor

5. Hyperparameter Tuning

Used GridSearchCV with KFold cross-validation (k=5)

Tuned max_depth, n_estimators, and other parameters for Random Forest

6. Evaluation Metrics

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

7. Results

Best Model: Random Forest Regressor

🌟 Key Learnings (updated)
1.Implemented an end-to-end ML pipeline combining preprocessing, modeling, and tuning

2.Applied unsupervised learning techniques to gain deeper insights into data patterns

3.Improved understanding of dimensionality reduction with PCA
