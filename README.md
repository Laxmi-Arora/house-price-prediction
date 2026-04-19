# 🏠 House Price Prediction

This project predicts house prices using Machine Learning techniques based on features like area, number of bedrooms, bathrooms, and more.

---

## 📊 Dataset
- King County House Sales Dataset (Kaggle)
- ~21,000 records
- Features include:
  - bedrooms
  - bathrooms
  - sqft_living
  - sqft_lot
  - floors
  - condition
- Target variable: **price**

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🤖 Models Used

### 1. Linear Regression
- R² Score: **0.70**
- Used as a baseline model

### 2. Random Forest Regressor
- R² Score: **0.86**
- Significantly improved performance over Linear Regression

---

## 📈 Model Evaluation Metrics

### Linear Regression:
- MAE: 127,474  
- RMSE: 212,520  
- R² Score: 0.70  

### Random Forest:
- R² Score: 0.86  

---

## 📉 Visualizations
- Price Distribution Histogram
- Feature Correlation Heatmap
- Living Area vs Price Scatter Plot
- Actual vs Predicted Prices

---

## ✅ Conclusion
- Linear Regression provided a good baseline with moderate accuracy.
- Random Forest Regressor improved performance significantly.
- The project demonstrates how advanced models can better capture complex relationships in real-world data.

---

## 🚀 Future Improvements
- Hyperparameter tuning (GridSearchCV)
- Feature engineering
- Try advanced models like XGBoost
- Deploy as a web application

---

## 👩‍💻 Author
Laxmi Arora
