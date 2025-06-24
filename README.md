# 🪙 Gold Price Prediction using Random Forest Regression

This project uses a *Random Forest Regressor* to predict gold prices based on various financial indicators. It demonstrates how machine learning can be applied in finance to forecast commodity prices.

---

## 📁 Files Included

- gold_price_prediction.ipynb – Jupyter Notebook containing the full implementation.
- gold_data.csv – Dataset with historical gold prices and related features.
- requirements.txt – List of Python dependencies.
- README.md – Project overview and instructions.

---

## 📊 Dataset

*Source:* Kaggle or public financial data  
*Features:*
- Date  
- Gold Price  
- Crude Oil Price  
- Silver Price  
- USD/INR Exchange Rate  
- Stock Market Indices  

---

## 🧠 Model Used

*Algorithm:* Random Forest Regressor  
- Handles complex, non-linear relationships  
- Reduces overfitting through ensemble learning  
- Offers feature importance scores  

---

## 🔁 Project Workflow

1. Load & Explore the Data
2. Handle Missing Values
3. Feature Selection & Engineering
4. Train-Test Split
5. Train Random Forest Regressor
6. Evaluate Performance (MAE, MSE, RMSE, R²)
7. Visualize Predictions & Feature Importance

---

## 📈 Results (Example)

| Metric   | Value  |
|----------|--------|
| R² Score | 0.95   |
| MAE      | 15.4   |
| RMSE     | 24.7   |

(Results will vary depending on the dataset and preprocessing steps)

---

## 📷 Visualizations

- Gold Price Trend Over Time  
- Correlation Heatmap  
- Feature Importance Plot  
- Actual vs Predicted Prices  

---

## 🛠 Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
