#🚗 Car Price Prediction Using Machine Learning

## Overview

This project predicts used car selling prices using machine learning techniques. The dataset contains over 15,000 vehicle records with features such as vehicle age, fuel type, transmission type, engine capacity, mileage, maximum power, and brand information.

Dataset: :contentReference[oaicite:0]{index=0}

## Dataset

- Source: CarDekho Used Car Dataset
- Records: 15,000+
- Target Variable: Selling Price

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Preprocessing
5. Model Training
6. Model Comparison
7. Feature Importance Analysis

## Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- XGBoost Regressor

## Results

| Model | R² Score |
|---------|---------:|
| Linear Regression | 0.8918 |
| Ridge Regression | 0.8918 |
| Lasso Regression | 0.8919 |
| Random Forest | 0.9339 |
| XGBoost | 0.9406 |

Best Model: **XGBoost Regressor**

## Key Findings

- Maximum power is the most important factor affecting car price.
- Vehicle age has a strong impact on resale value.
- Engine capacity positively influences selling price.
- Premium brands generally retain higher value.
- Petrol and Diesel vehicles dominate the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

## Conclusion

A machine learning model was developed to predict used car prices using vehicle characteristics. Among all models tested, XGBoost achieved the best performance with an R² score of 0.9406.
