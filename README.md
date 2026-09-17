# Supermarket Sales Prediction

A machine learning project for predicting supermarket transaction sales using Python.

## Project Overview

This project analyzes supermarket sales data and builds machine learning models to predict total sales for individual transactions.

The project covers data cleaning, exploratory data analysis, feature engineering, data visualization, model building, and model evaluation.

## Objective

The main objective is to use historical supermarket transaction data to develop a model that can predict sales and identify important factors that influence transaction sales.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Data visualization
5. Feature engineering
6. Data preparation for machine learning
7. Model training
8. Model evaluation
9. Feature importance analysis
10. Conclusion

## Machine Learning Models

The following regression models were developed and evaluated:

- Linear Regression
- Decision Tree
- Random Forest

## Model Results

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Random Forest | 6.67 | 10.13 | 0.9984 |
| Decision Tree | 9.17 | 14.26 | 0.9969 |
| Linear Regression | 59.78 | 80.10 | 0.9014 |

## Key Findings

The analysis identified important patterns in supermarket transactions across product lines, branches, customer types, genders, payment methods, and quantities.

The Random Forest model produced the strongest results among the models evaluated in this project. Quantity and Unit Price were identified as important predictors of sales.

## Files

- `Supermarket Sales Prediction.ipynb` — Complete Jupyter/Google Colab notebook containing the analysis and machine learning workflow.
- `SuperMarket Analysis.csv` — Dataset used for the analysis.

## Conclusion

This project demonstrates how Python and machine learning can be used to analyze supermarket transaction data and predict sales.

The project also demonstrates practical skills in data preprocessing, exploratory data analysis, visualization, regression modeling, model evaluation, and feature importance analysis.
