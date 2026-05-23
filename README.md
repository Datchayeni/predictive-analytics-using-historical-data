# Predictive Analytics Using Historical Data
Machine Learning project for predicting BigMart outlet sales using historical data. Includes data preprocessing, label encoding, regression model building, prediction, accuracy evaluation, and data visualization using Python, Pandas, Matplotlib, and Scikit-learn.

## Objective
The main objective of this project is to build a regression model capable of predicting outlet sales based on various product and outlet features.

# Tools and Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

# Dataset Information
The project uses the BigMart Sales Dataset containing features such as:
- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Size
- Outlet Location Type
- Outlet Type
- Item Outlet Sales

# Project Workflow

## 1. Data Preprocessing
- Loaded dataset using Pandas
- Checked dataset structure and missing values
- Handled missing values using:
  - Mean
  - Mode

## 2. Feature Engineering
- Applied Label Encoding on categorical columns
- Prepared feature variables and target variable

## 3. Model Building
- Used Linear Regression algorithm
- Split dataset into training and testing data

## 4. Model Training and Prediction
- Trained the regression model
- Generated predictions using test data

## 5. Model Evaluation
Evaluated model performance using:
- Mean Absolute Error (MAE)
- R2 Score

## 6. Data Visualization
Created visualizations including:
- Actual vs Predicted Sales graph
- Predicted vs Actual Sales comparison
- Sales Distribution graph
- Item MRP vs Sales scatter plot

# Libraries Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_absolute_error, r2_score
```

# Output
- Successfully trained a regression model for sales prediction
- Generated prediction results and evaluation metrics
- Visualized sales trends and prediction performance

# Project Files
- predictive_analytics.ipynb
- bigmart.csv
- README.md
- Graph screenshots

## Conclusion
This project demonstrates the complete workflow of a Machine Learning regression problem including preprocessing, model building, evaluation, and visualization using historical sales data.
