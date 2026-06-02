# 🎓 Student Placement Predictor (Machine Learning)

## 📌 Project Overview
The **Student Placement Predictor** is a Machine Learning application that predicts whether a student is likely to get placed based on their academic and skill metrics. It evaluates key factors like CGPA, Aptitude, Communication Skills, Project counts, and Internship experience to provide a data-driven prediction.

## 🚀 Features
- **Data Preprocessing:** Automatically maps categorical data (Yes/No) into numerical formats.
- **Model Training:** Utilizes Scikit-Learn (Logistic Regression / Decision Tree) to train on student datasets.
- **Model Serialization:** Uses `joblib` to dynamically save the trained model (`placement_model.pkl`) and load it instantly for future predictions without retraining.
- **Visual Analytics:** Generates bar charts and scatter plots using `matplotlib` to visualize data distribution.
- **Interactive CLI:** An easy-to-use Command Line Interface for users to input new student data and get instant probability scores.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Matplotlib, Joblib

## 📂 Project Structure
```text
├── main.py                # Main application script (Training & Prediction)
├── students_data.csv      # Dataset containing student records
├── placement_model.pkl    # Serialized ML model (Auto-generated after 1st run)
├── requirements.txt       # List of dependencies
└── README.md              # Project documentation
