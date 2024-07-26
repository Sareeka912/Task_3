Heart Disease UCI Dataset Project

This Task utilizes the Heart Disease UCI dataset from Kaggle to build and evaluate predictive models for heart disease diagnosis. The goal is to explore the dataset, apply various machine learning algorithms, and optimize model performance through feature engineering and hyperparameter tuning.

Project Steps

1. Dataset
 Heart Disease UCI dataset from Kaggle.
2. Data Loading
Loaded the dataset using pandas library.
3. Data Cleaning
   Duplicate rows and not usefull features are drop in  data cleaning to prepare the dataset for analysis.
4. Missing Values Handling
Handled missing values separately for categorical and numerical columns using mean and mode stretegy.
5. Exploratory Data Analysis (EDA)
Conducted EDA to understand the data distribution, identify patterns, and visualize relationships between features.
6. Data Encoding and Standardization
Encoded categorical features and standardized numerical features to prepare the data for modeling.
7. Model Application
Applied three machine learning algorithms:
Logistic Regression
Decision Tree
Linear Discriminant Analysis (LDA)
Performance Evaluation: Compared the performance of these algorithms and determined that Logistic Regression performed the best.
8. Feature Engineering
Feature Transformation: Applied transformations to improve feature representation.
Feature Generation: Created new features to enhance model performance.
Polynomial Features: Used polynomial features to capture interactions between variables.
Feature Selection: Employed techniques like Chi-Square, Recursive Feature Elimination (RFE), and RandomForest for feature selection.
9. Hyperparameter Tuning
Conducted hyperparameter tuning to optimize model performance and improve accuracy.
