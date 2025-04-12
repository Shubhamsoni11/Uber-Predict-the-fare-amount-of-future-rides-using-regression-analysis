# 🚖 Uber Fare Prediction Model

This project focuses on predicting the fare amount of Uber rides in New York City using historical trip data and machine learning algorithms. It demonstrates data preprocessing, feature engineering, and regression modeling techniques using Python.

## 📌 Problem Statement

Given the pickup and dropoff coordinates, along with the timestamp of a ride, predict the fare amount of the trip. This helps Uber improve pricing strategies and detect potential fare anomalies.

## 📊 Dataset

- Features:
  - Pickup datetime
  - Pickup & Dropoff coordinates
  - Passenger count
  - Fare amount (target)

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Workflow

1. **Data Cleaning & EDA**
   - Removed nulls, duplicates, and outliers
   - Visualized spatial and temporal patterns

2. **Feature Engineering**
   - Calculated distance using Haversine formula
   - Extracted time-based features from pickup datetime

3. **Model Building**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Performance evaluated using RMSE & R²

4. **Model Tuning**
   - Hyperparameter tuning using GridSearchCV

## 📈 Results

- Random Forest performed best with tuned parameters

## 📁 Project Structure

