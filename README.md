# ✈️ Flight Fare Prediction

This machine learning project aims to predict airline ticket prices using various flight-related features such as airline, source, destination, duration, and number of stops.

---

## 📁 Dataset

- **Source**: Provided Excel file (`Data_Train.xlsx`)
- **Size**: [Mention number of rows/columns after `.shape`]
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

### 4. Evaluation
- Metrics: R² Score, MAE, RMSE
- Model comparison table

---

## 📊 Results

| Model           | R² Score | RMSE     | MAE      |
|----------------|----------|----------|----------|
| Linear Regression | 0.XXX     | XXX.XX   | XXX.XX   |
| Random Forest     | 0.XXX     | XXX.XX   | XXX.XX   |
| XGBoost           | 0.XXX     | XXX.XX   | XXX.XX   |

✅ **Best model**: [Write your best-performing model here]

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

