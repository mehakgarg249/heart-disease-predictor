# heart-disease-predictor
❤️ Heart Disease Prediction System

A machine learning project that predicts whether a person is at risk of heart disease using medical attributes and a trained classification model.
The app provides a Streamlit-based interface where users can input health parameters and instantly get prediction results.

🧠 Project Overview

This project aims to identify individuals who may have heart disease by analyzing key clinical features such as:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Maximum Heart Rate

ST Depression (Oldpeak)

Exercise-Induced Angina

ST Slope

A fully trained and optimized machine learning pipeline (saved in .joblib format) powers the prediction system.

🚀 Features

Interactive Streamlit App for quick prediction

Pretrained ML model for real-time inference

User-friendly input fields to simulate medical check-up values

Clear output displaying:

✅ No Heart Disease Detected

🚨 High Risk of Heart Disease

🧩 Technologies Used

Python 3.10+

Streamlit

Pandas, NumPy

Scikit-learn

Joblib

Jupyter Notebook

🧮 How It Works

The user inputs essential health parameters:

Age, Sex, Chest Pain Type, BP, Cholesterol

Max Heart Rate, Oldpeak, Exercise Angina, ST Slope

The system preprocesses and formats these values according to the trained pipeline.

The data is passed into the trained ML model.

The model predicts:

0 → No Heart Disease

1 → Heart Disease Present

📊 Model Training

Model training and evaluation were carried out in pipeline_model.ipynb, including:

Data preprocessing and cleaning

Handling missing values

Feature scaling and transformation

Model selection and hyperparameter tuning

Evaluation using:

Accuracy

Precision, Recall, F1-score

Confusion Matrix

Saving the optimized model using joblib

🧠 Future Enhancements

Add real-time patient monitoring API

Integrate medical visualization dashboard

Deploy on cloud platforms for easy access

Add explainability features (e.g., SHAP analysis)

Improve UI with charts and data insights
