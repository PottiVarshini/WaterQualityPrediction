# 💧 Water Quality Prediction using Machine Learning

This project predicts the concentration levels of key water pollutants (like O₂, NO₃, NO₂, SO₄, PO₄, and Cl) based on the **Year** and **Station ID** using a trained **Random Forest Regressor** model.

---

##  Problem Statement

Monitoring water quality across various locations is critical for environmental sustainability. However, manual sampling is resource-intensive. This project provides a data-driven way to predict water pollutant levels, helping in early intervention and planning.

---

## 🎯 Learning Objectives

- Understand the working of the **Random Forest Regressor**
- Train a model to predict pollutant levels from basic inputs
- Evaluate model performance using **RMSE (Root Mean Squared Error)**
- Build a Streamlit UI to make predictions user-friendly

---

## 🧪 Technologies Used

- **Python**
- **Pandas**, **NumPy** — Data manipulation
- **Scikit-learn** — Model training
- **Joblib** — Model serialization
- **Git & GitHub** — Version control
- **Streamlit** — Web-based interactive UI
- **Git LFS** — Handling large `.pkl` files (>25MB)

---

## 🧠 Methodology

1. Collected and cleaned water quality data
2. Encoded `Station ID` using one-hot encoding
3. Trained a **Random Forest Regressor** to predict pollutant levels
4. Evaluated model using RMSE
5. Built a Streamlit app for easy user input and real-time prediction

---

## 📈 Model Features

- Inputs:
  - `Year`
  - `Station ID`
- Outputs:
  - Predicted values for:
    - Oxygen (O₂)
    - Nitrate (NO₃)
    - Nitrite (NO₂)
    - Sulphate (SO₄)
    - Phosphate (PO₄)
    - Chloride (Cl)

---
