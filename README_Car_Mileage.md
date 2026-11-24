# Car Mileage Prediction Using Multiple Linear Regression

## Overview
This project predicts a car's fuel efficiency in miles per gallon (MPG) using Multiple Linear Regression and vehicle specifications.

## Problem Statement
Car mileage depends on several characteristics, including engine size, horsepower, weight, and model year. The goal is to learn how these features relate to MPG and predict mileage for a car.

## Objectives
- Load and clean the Auto MPG dataset.
- Perform exploratory data analysis (EDA).
- Visualize feature relationships and correlations.
- Train Single Linear Regression and Multiple Linear Regression models.
- Evaluate performance using R², Adjusted R², and RMSE.
- Compare actual and predicted MPG.
- Predict MPG for a new car.

## Dataset
- **Dataset:** Auto MPG
- **Source:** UCI Machine Learning Repository
- **Link:** https://archive.ics.uci.edu/dataset/9/auto+mpg
- **Target:** `mpg`
- **Features:** `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, `model_year`, `origin`
- **Cleaned records:** 392

## Tools and Libraries
Python, Jupyter Notebook / Google Colab, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## Workflow
1. Import the required libraries.
2. Load and inspect the dataset.
3. Clean the data and handle missing values.
4. Perform EDA and create visualizations, including a correlation heatmap.
5. Separate input features (`X`) and target (`y`).
6. Split the data into 80% training and 20% testing using `random_state=42`.
7. Train a Single Linear Regression model using car weight.
8. Train a Multiple Linear Regression model using all seven listed features.
9. Evaluate the models using R², Adjusted R², and RMSE.
10. Plot actual versus predicted MPG.
11. Predict the mileage of a new car.

## Model and Results
**Main algorithm:** Multiple Linear Regression

Reported test-set results:
- **R²:** 0.7902
- **Adjusted R²:** 0.7695
- **RMSE:** 3.2727 MPG

These values reflect the project run and may change if the data preparation, features, or split changes.

## How to Run
1. Clone or download this repository.
2. Open `multiple_linear_regression_car_mileage.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook cells in order.
4. If the notebook downloads the dataset, ensure internet access is available.

## Repository Contents
- `multiple_linear_regression_car_mileage.ipynb` — data preparation, EDA, model training, evaluation, and prediction.
- `README.md` — project documentation.

## Conclusion
The project demonstrates how multiple vehicle features can be used to predict fuel efficiency. On the reported test split, the Multiple Linear Regression model achieved an R² score of 0.7902 and an RMSE of 3.2727 MPG.

## Author
Add your name, roll number, college, and course details here.
