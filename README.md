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


<table>
  <tr>
    <td>
      <strong>📈 Actual vs Predicted House Prices</strong><br>
      <img src="output_images/Actual vs Predicted House Prices.png" width="400">
    </td>
    <td>
      <strong>📉 Residuals Distribution</strong><br>
      <img src="output_images/Residuals Distribution.png" width="400">
    </td>
  </tr>
  <tr>
    <td>
      <strong>🔥 Feature Correlation Heatmap</strong><br>
      <img src="output_images/Feature Correlation Heatmap.png" width="400">
    </td>
    <td>
      <strong>🔍 Pairwise Feature Relationships</strong><br>
      <img src="output_images/Pairwise Feature Relationships.png" width="400">
    </td>
  </tr>
</table>


---

---
## 🚀 Getting Started

1. Clone the repository  
   `git clone https://github.com/yourusername/house-price-linear-regression.git`  
   `cd house-price-linear-regression`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Run the notebook  
   Open `house_price_regression.ipynb` in Jupyter or Colab.

## 🧠 Model Used  
LinearRegression() from sklearn.linear_model


## 📌 License  
This project is licensed under the MIT License – see the LICENSE file for details.

---

## ✍️ Author  
👤 **Shreyak Mukherjee**  
📂 GitHub: [shreyakmukherjee](https://github.com/shreyakmukherjee)  
🔗 LinkedIn: [linkedin.com/in/shreyakmukherjee](https://www.linkedin.com/in/shreyak-mukherjee-203558275/)  
Feel free to connect or explore more projects!

---
