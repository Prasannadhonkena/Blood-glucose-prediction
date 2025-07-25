# 🩺 Blood Glucose Level Prediction – ML Web App for Glycemic Control

## 🧭 Overview

This project is a **Flask-based machine learning web application** that predicts **blood glucose levels** to assist diabetic patients and healthcare professionals in managing blood sugar levels. By analyzing patient health metrics, lifestyle habits, and historical glucose readings, the system forecasts future glucose values and alerts potential glycemic risks.

This predictive model supports **personalized care**, **early intervention**, and **optimized treatment planning** in diabetes management.

---

## 🚀 Features

- 🔢 Predicts future **blood glucose levels** using:
  - Age, BMI, insulin, glucose levels, blood pressure, etc.
- 🤖 Trained using **ML models** like:
  - Random Forest
  - XGBoost
  - SVM or Linear Regression
- 🌐 Flask-based web interface for easy input and prediction
- 📊 Real-time display of prediction result
- 📁 Extendable to integrate with wearable device data

---

## 🧠 Machine Learning

- **Target:** Blood glucose level (regression) or glycemic control category (classification)
- **Best model performance:** e.g., Random Forest with RMSE ~8.3 mg/dL

---

## 📁 Project Structure
glucose-predictor-ml/
├── data/
│   └── glucose_data.csv             # Dataset with patient records
├── models/
│   └── glucose_model.pkl            # Trained ML model
├── app/
│   ├── predictor.py                 # Prediction logic
│   ├── utils.py                     # Helper functions
│   └── web_app.py                   # Streamlit or Flask web app
├── notebooks/
│   └── EDA_and_Modeling.ipynb       # Exploratory Data Analysis and training
├── README.md
├── requirements.txt                 # Python dependencies
└── LICENSE