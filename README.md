# 🎓 Student Final Grade (G3) Predictor

This is an interactive Streamlit web application that predicts a student's final grade (G3) based on various academic and behavioral inputs. The model is trained on the UCI Student Performance dataset using a Random Forest Regressor optimized with GridSearchCV.

---

## 📌 Project Overview

This project explores the relationship between student characteristics and their final academic performance. It uses machine learning to predict the final grade (G3) based on input features such as first and second period grades, study time, past failures, and absences.

---

## 🚀 Key Features

- 🔢 Input sliders and dropdowns for:
  - G1 (First Period Grade)
  - G2 (Second Period Grade)
  - Study Time
  - Past Class Failures
  - Number of Absences
- ⚙️ Machine Learning model (Random Forest Regressor) with tuned hyperparameters
- 📊 Real-time prediction of the final grade (G3)
- 🌐 Web app built with Streamlit — deployable and interactive

---

## 🛠 Technology Stack

- **Python**
- **Streamlit**
- **Scikit-learn**
- **NumPy**
- **Joblib**

---

## 🧠 Model Development

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature selection using correlation heatmaps and domain logic
- Model training using Random Forest Regressor
- Hyperparameter tuning using `GridSearchCV`
- Model evaluation using R² score and error metrics

---

## ⚙️ How to Run the App Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Mounika-annareddy14/student-performance-app.git
cd student-performance-app

## 📂 Repository Structure
bash
Copy
Edit
├── app.py                  # Streamlit application code

├── best_rf_model.pkl       # Pre-trained Random Forest model

├── requirements.txt        # Python dependencies

├── Student_Performance.ipynb  # Notebook with model training

└── README.md               # Project documentation

## 📊 Model Insights
G1 and G2 (first and second period grades) had the highest impact on final grade (G3)

Study time positively influenced performance

High absences and prior failures correlated with lower grades

The best model achieved an R² score of 0.85, indicating strong predictive power

📎 Dataset Reference
UCI Machine Learning Repository – Student Performance Data

