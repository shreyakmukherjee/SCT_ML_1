# 🏡 House Price Prediction using Linear Regression

This repository contains a notebook for predicting house prices using a **Linear Regression** model on the popular [Kaggle House Price dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques). 

📌 **Task Objective:**
Predict the sale price of houses based on:
- 🧱 Total square footage (`GrLivArea`)
- 🛏️ Number of bedrooms (`BedroomAbvGr`)
- 🛁 Number of bathrooms (combined `FullBath` and `HalfBath` into `TotalBath`)

---

## 🔧 Features

- 🔹 Data preprocessing with feature engineering
- 🔹 Standardization using `StandardScaler`
- 🔹 Linear regression model with evaluation metrics (RMSE, R²)
- 🔹 Multiple visualizations:
  - 📉 Actual vs Predicted plot
  - 📊 Residuals distribution
  - 🔥 Correlation heatmap
  - 📌 Regression coefficients bar plot

---

## 📂 Dataset

- **Source:** [House Price Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- **Files Used:** `train.csv`

---


## 🛠️ Workflow

1. **Data Preprocessing** 🔧
   - Selected relevant features
   - Engineered `TotalBath = FullBath + 0.5 × HalfBath`
   - Standardized input features using `StandardScaler`

2. **Model Building** 🤖
   - Used `LinearRegression()` from `sklearn`
   - Trained on 80% of the data, tested on 20%

3. **Evaluation Metrics** 📊
   - RMSE (Root Mean Squared Error)
   - R² Score (Coefficient of Determination)

4. **Visualizations** 📈
   - 📉 Loss Curves
   - 🎯 Actual vs Predicted Plot
   - 📊 Residual Distribution
   - 🧱 Feature Correlation Heatmap
   - 📌 Regression Coefficients Bar Plot

---

## ✅ Results

| Metric        | Value      |
|---------------|------------|
| Train RMSE    | 15349.02   |
| Test RMSE     | 33980.44   |
| Train R²      | 0.96       |
| Test R²       | 0.85       |


---

