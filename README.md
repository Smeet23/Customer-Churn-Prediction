# 📉 Telco Customer Churn Prediction

A complete end-to-end machine learning project to analyze, model, and visualize customer churn behavior using the Telco dataset.


## 🔍 Project Overview

This project predicts whether a telecom customer will churn based on their account, demographic, and service-related features. It includes data preprocessing, exploratory analysis, model building, evaluation, and insights visualization.

## 📁 Dataset

- **Source**: IBM Sample Dataset - Telco Customer Churn
- **Rows**: ~7,000
- **Target Variable**: `Churn` (Yes/No)
- **Key Features**:
  - Customer tenure
  - Contract type
  - Internet and phone services
  - Monthly and total charges
  - Payment methods
  - Gender, senior citizen, partner/dependent status

## 🔧 Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `pandas`, `numpy` — Data Handling  
  - `matplotlib`, `seaborn` — Visualization  
  - `scikit-learn` — Machine Learning (Random Forest, Label Encoding, Scaling)  
  - `Jupyter Notebook` — Development Environment  
- **Model**: Random Forest Classifier  
- **Evaluation**: Accuracy, Confusion Matrix, Classification Report

## 📊 Key Steps

1. **Data Preprocessing**
   - Converted `TotalCharges` to numeric
   - Filled missing values with mean
   - Encoded categorical features
   - Feature scaling with `StandardScaler`

2. **Exploratory Data Analysis (EDA)**
   - Churn rate by contract type, service usage, and tenure
   - Correlation heatmaps and boxplots

3. **Modeling**
   - Binary classification using Random Forest
   - Train/test split (80/20)
   - Accuracy achieved: ~80–85%

4. **Visualization**
   - Charts showing churn distribution, feature importance
   - Optional dashboard image (e.g., Tableau/Matplotlib)

## 📈 Results

| Metric     | Score |
|------------|-------|
| Accuracy   | ~82%  |
| Precision  | ~0.80 |
| Recall     | ~0.83 |
| F1-score   | ~0.81 |

## 🚀 Future Enhancements

- Add GridSearchCV for hyperparameter tuning
- Test other models (e.g., XGBoost, SVM)
- Perform feature importance using SHAP
- Build an interactive dashboard using Streamlit

## 👤 Author

**Smeet Agrawal**  
📧 [smeetagrawal2003@gmail.com](mailto:smeetagrawal2003@gmail.com)

---

> ⚠️ Note: The dataset used in this project is publicly available and intended for educational use.
