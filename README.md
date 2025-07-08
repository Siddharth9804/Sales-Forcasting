# 📊 Sales Forecasting Project
---

## ✅ Dataset Details:
- Total Records: 2,823
- Key Columns:
  - `ORDERDATE`: Date of order  
  - `SALES`: Sales Amount (Target)
  - `MONTH_ID`, `YEAR_ID`: Additional Date Features

---

## ✅ Project Goals:
- Analyze and visualize historical sales data.
- Predict future sales using **Machine Learning (Linear Regression)**.

---

## ✅ Tools & Libraries:
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Google Colab

---

## ✅ Steps:
1. Data Cleaning & Feature Engineering (Extract Year, Month, Day).
2. Exploratory Data Analysis (EDA) & Visualization.
3. Model Building:
   - Train-Test Split  
   - Linear Regression Model  
   - Model Evaluation (MAE, RMSE, R²)
4. Future Sales Forecasting (Next 30 Days).
5. Visualization of Actual vs Forecasted Sales.

---

## ✅ Model Performance: 
Mean Absolute Error (MAE):1490.05\n
Mean Squared Error (MSE) :3,870,879.67\n
Root Mean Squared Error (RMSE):1967.46\n
R² Score :0.0028 (near zero)

---

## ✅ Future Enhancements:
- Try **ARIMA, XGBoost** for better time-series forecasting.
- Incorporate additional features like **PRODUCTLINE**, **DEALSIZE**.
- Hyperparameter Tuning.
