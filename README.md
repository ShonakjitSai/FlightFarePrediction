# ✈️ Basic/Intermediate ML-Flight Fare Prediction

This machine learning project aims to predict airline ticket prices using various flight-related features such as airline, source, destination, duration, and number of stops.

---

## 📁 Dataset

- **Source**: Provided Excel file (`Data_Train.xlsx`)
- **Key Features**:
  - Airline
  - Source
  - Destination
  - Route
  - Duration
  - Total Stops
  - Price

---

## 🔍 Project Workflow

### 1. Data Exploration
- Checking data types, missing values
- Visualizing categorical and numerical features

### 2. Data Preprocessing
- Dropping nulls
- Feature Engineering (duration, date columns)
- Label Encoding / One-Hot Encoding
- Train-Test Split

### 3. Modeling
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Ridge Regression
- Lasso Regression
- Gradient Boosting

### 4. Evaluation
- Metrics: R² Score, MAE, RMSE
- Model comparison table

---

## 📊 Results


| Model              | R² Score |   RMSE   |   MAE   |
|--------------------|----------|----------|---------|
| Linear Regression  | 0.6902   | 2484.39  | 1711.12 |
| Ridge Regression   | 0.6901   | 2484.71  | 1712.73 |
| Lasso Regression   | 0.6902   | 2484.36  | 1711.10 |
| Random Forest      | 0.8596   | 1672.28  |  732.49 |
| Gradient Boosting  | 0.7789   | 2098.71  | 1284.83 |
| XGBoost            | 0.8442   | 1761.71  |  947.67 |


✅ **Best model**: RandomForestRegressor

---



