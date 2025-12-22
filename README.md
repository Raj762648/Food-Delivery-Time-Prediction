# 🍔 Food Delivery Time Prediction

## 📌 Project Overview
Accurate food delivery time estimation plays a crucial role in improving customer satisfaction and optimizing logistics for food delivery platforms.  
This project focuses on predicting **food delivery time** using machine learning regression models based on order, restaurant, and delivery-related features.

The problem is modeled as a **supervised regression task**, where the objective is to produce reliable and well-generalized predictions on unseen data.

---

## 🎯 Objective
- Predict food delivery time (continuous target variable)
- Build and compare ensemble-based regression models
- Evaluate models using **RMSE, MAE, and R² Score**
- Select a stable and production-ready model

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - NumPy, Pandas  
  - Matplotlib, Seaborn  
  - scikit-learn  
  - XGBoost  

---

## 📊 Models Implemented
- Random Forest Regressor  
- XGBoost Regressor  

---

## 📈 Model Performance Summary

### 🔹 Random Forest Regressor

#### Training Set
- Root Mean Squared Error (RMSE): **9.6391**
- Mean Absolute Error (MAE): **6.3845**
- R² Score: **0.8062**

#### Test Set
- Root Mean Squared Error (RMSE): **10.0692**
- Mean Absolute Error (MAE): **7.0245**
- R² Score: **0.7975**

---

### 🔹 XGBoost Regressor

#### Training Set
- Root Mean Squared Error (RMSE): **8.3073**
- Mean Absolute Error (MAE): **5.5539**
- R² Score: **0.8561**

#### Test Set
- Root Mean Squared Error (RMSE): **9.7711**
- Mean Absolute Error (MAE): **7.0358**
- R² Score: **0.8093**

---

## 🧠 Model Interpretation & Insights
- Both models demonstrate **good predictive performance** with R² scores close to **0.80** on the test set.
- **Random Forest Regressor shows excellent generalization**, with minimal performance gap between training and test data.
- **XGBoost Regressor achieves lower training error** but exhibits mild overfitting, as seen from the larger drop in test R² and increase in RMSE.
- RMSE values being only slightly higher than MAE indicate **well-distributed prediction errors** without extreme outliers.

---

## 📌 Key Takeaways
- Random Forest provides **stable and reliable predictions**, making it suitable for real-world deployment.
- XGBoost requires additional regularization and tuning to further improve generalization.
- Model stability is prioritized over aggressive fitting for noisy regression problems like delivery time prediction.

---
