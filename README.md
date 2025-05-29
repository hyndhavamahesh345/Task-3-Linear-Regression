## 📌 Task 3: AI & ML Internship Assignment
# Task-3-Linear-Regression

This repository contains my implementation of **Linear Regression** as part of the AI/ML internship at Elevate Labs. The goal was to build a simple regression model using the **House Price Prediction dataset**, evaluate its performance using metrics, and visualize the results.

---

## 🎯 Objective

Learn and implement key steps in linear regression including:

- Building a simple linear regression model  
- Evaluating model performance using standard metrics  
- Visualizing the regression line  
- Interpreting regression coefficients  

---

## 🛠 Tools Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib

---

## 📂 Dataset

The dataset used is the [House Price Prediction Dataset](https://www.kaggle.com/datasets/ejamesc/house-price-prediction) from Kaggle.  
It contains various features related to residential properties, including:

- `area` (size of the house in square feet)
- `bedrooms`
- `bathrooms`
- `stories`
- `parking`
- `price` (target variable – house price in ₹)

This dataset is used to train and evaluate a simple linear regression model to predict house prices based on area.


---

## 🧪 Steps Performed

### 1. Data Exploration
- Inspected data types, column names, and data preview
- Checked for missing values and basic statistics

### 2. Feature Selection
- Selected `area` as the independent variable (X)
- Selected `price` as the target variable (y)

### 3. Train-Test Split
- Used `train_test_split` to divide data (80% train, 20% test)

### 4. Model Training
- Used `LinearRegression` from `sklearn.linear_model`
- Fitted the model to training data

### 5. Model Evaluation
- Calculated the following metrics:
  - **MAE (Mean Absolute Error)**: `1,474,748.13`
  - **MSE (Mean Squared Error)**: `3,675,286,604,768.18`
  - **R² Score**: `0.2729` (Model explains ~27% variance in house prices)

### 6. Coefficients Interpretation
- **Intercept**: `2,512,254.26`
- **Coefficient (area)**: `425.73`
  - For each additional unit of area, the house price increases by approx ₹425.73

### 7. Visualization
- Scatter plot of actual prices vs area
- Regression line overlay using Matplotlib

---

## 📊 Visualizations

- Scatter plot of actual vs predicted prices  
- Regression line showing model fit  

> 📌 See `images/regression_plot.png` in the repo for the plot.

---

## 📚 Key Learnings

- Hands-on implementation of a simple linear regression model
- Importance of evaluation metrics like MAE, MSE, and R²
- How to interpret regression coefficients
- Visualizing regression results to understand model fit
- Real-world application on housing price prediction

---
