# Predicting House Prices Using Linear Regression

## Overview

This project develops a machine learning model to predict house prices using the California Housing dataset. The analysis follows a complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, and model serialization.

The objective is to understand how housing-related features influence property values and to build a predictive model using Linear Regression.

## Dataset

The project uses the California Housing dataset, which contains information about housing districts, including demographic, geographic, and economic features.

### Features

* Median Income
* Housing Median Age
* Average Rooms
* Average Bedrooms
* Population
* Average Occupancy
* Latitude
* Longitude

### Target Variable

* Median House Value

## Project Workflow

1. Data Loading and Preparation
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Scaling using StandardScaler
5. Train-Test Split
6. Linear Regression Model Training
7. Model Evaluation
8. Model Serialization using Pickle

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Model Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score
* Adjusted R² Score

These metrics help assess how accurately the model predicts housing prices and how well the input features explain variations in house values.

## Repository Contents

* `Predicting_House_Prices.ipynb` — Main notebook containing the analysis and model development workflow.
* `Income Dataset.csv` — Dataset used for training and evaluation.
* `model.pkl` — Serialized trained Linear Regression model.
* `.gitignore` — Git ignore configuration.

## Key Learning Outcomes

* Exploratory Data Analysis (EDA)
* Data preprocessing techniques
* Feature scaling and normalization
* Building Linear Regression models
* Model evaluation and interpretation
* Model persistence using Pickle
* Version control with Git and GitHub

## Future Improvements

* Compare Linear Regression with more advanced models such as Random Forest and XGBoost.
* Perform hyperparameter tuning.
* Add feature engineering techniques.
* Deploy the trained model as a web application.

## Author

Debargha Paul
