# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of used cars using machine learning regression algorithms. The workflow includes data preprocessing, feature engineering, exploratory data analysis, model training, evaluation, and feature importance analysis.

The goal is to estimate car prices based on vehicle characteristics such as age, fuel type, transmission, kilometers driven, and present market price.

---

## 🎯 Objectives

- Analyze car-related features.
- Perform complete data preprocessing.
- Engineer meaningful features.
- Train multiple regression models.
- Compare model performance.
- Predict selling prices of cars.
- Understand real-world applications of price prediction.

---

## 📂 Dataset Features

Typical features include:

- Car Name
- Year
- Present Price
- Selling Price (Target)
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Number of Owners

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📈 Project Workflow

### Data Preprocessing

- Remove duplicates
- Handle missing values
- Drop unnecessary columns
- Encode categorical variables
- Feature engineering:
  - Car Age

### Exploratory Data Analysis

- Price distribution
- Correlation heatmap
- Pairplot
- Scatter plots
- Feature relationships

### Model Development

Regression models used:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Extra Trees Regressor
- Support Vector Regressor
- K-Nearest Neighbors Regressor

### Model Evaluation

Evaluation metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Model Interpretation

- Feature Importance
- Actual vs Predicted Plot
- Residual Analysis

---

## 📊 Visualizations

- Correlation Matrix
- Histogram
- Boxplot
- Scatter Plots
- Pairplot
- Residual Distribution
- Feature Importance

---

## 📌 Key Findings

- Present Price is the strongest predictor.
- Car Age negatively affects selling price.
- Higher mileage generally reduces resale value.
- Fuel type and transmission influence price.
- Ensemble models outperform simple linear regression.

---

## 💡 Applications

- Used Car Marketplaces
- Automobile Dealerships
- Insurance Companies
- Vehicle Financing
- Fleet Management
- Online Price Recommendation Systems

---

## 📁 Output

- Trained Regression Models
- Feature Importance Analysis
- Price Prediction
- Saved Model (.pkl)

---

## 🚀 Future Improvements

- Hyperparameter tuning
- XGBoost and LightGBM
- Cross-validation
- Streamlit Web Application
- Deployment using Flask/FastAPI

---
