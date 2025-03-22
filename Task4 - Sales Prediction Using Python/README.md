# 📊 Sales Prediction Using Python

## 📌 Project Overview

This project demonstrates how to predict sales using Linear Regression in Python. The dataset includes advertising expenditures on TV, radio, and newspapers to analyze their impact on sales. The goal is to build a machine learning model that provides accurate sales predictions based on advertising budgets.

## 🛠️ Technologies Used

- **Python** 🐍  
- **Pandas & NumPy** for data manipulation 📊  
- **Matplotlib & Seaborn** for data visualization 🎨  
- **Scikit-learn** for machine learning 🤖  

## 📂 Dataset

The dataset contains the following features:

- **TV**: Advertising budget for TV 📺  
- **Radio**: Advertising budget for radio 📻  
- **Newspaper**: Advertising budget for newspapers 📰  
- **Sales**: The target variable representing sales volume 📈  

## 📊 Model Performance

The linear regression model achieved the following evaluation metrics:

| **Metric**               | **Value** | **Interpretation**                     |
|--------------------------|-----------|----------------------------------------|
| Mean Squared Error (MSE) | 2.9078    | Lower values indicate better fit       |
| R² Score                 | 0.9059    | 90.59% variance explained by the model |

**Key Insights:**
- The high R² score (0.9059) indicates strong predictive power
- Low MSE suggests accurate prediction of sales figures
- Model effectively captures relationships between ad spending and sales

**Visual Insights:**
- Tight clustering around diagonal line indicates accurate predictions
- Random residual pattern confirms good model fit
- Normally distributed errors validate regression assumptions