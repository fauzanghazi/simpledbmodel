# 🧮 Revenue Prediction Dashboard

A simple end-to-end machine learning web app built with **Streamlit** that predicts revenue based on sales data.  
Developed as part of **MRTB2173 – Agile Data Science (Activity 5.2)**.

---

## 🚀 Overview

This project demonstrates how to:
- Train a **Linear Regression** model using `scikit-learn`
- Preprocess categorical features with `OneHotEncoder`
- Save and load the model with `joblib`
- Deploy an interactive **Streamlit** dashboard for real-time revenue predictions

The deployed app is available here:  
👉 **[Live Demo on Streamlit Cloud](https://mrtb2173-5-2.streamlit.app)**

---

## 🧰 Project Structure

simpledbmodel/  
├── sales.csv — *Sample dataset*  
├── train_model.py — *Script to train and save regression model*  
├── revenue_model.pkl — *Trained ML model (saved with joblib)*  
├── predictive_dashboard.py — *Streamlit web app*  
├── requirements.txt — *Dependencies*  
└── README.md — *Project documentation*
