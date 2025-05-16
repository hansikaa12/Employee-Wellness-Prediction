# 👩‍💼 Employee Wellness Prediction

## 📌 Problem Statement

Employee wellness is a key factor in organizational success, affecting productivity, job satisfaction, and retention. Predicting employee wellness based on demographic and workplace-related factors allows organizations to proactively address employee needs and improve overall wellbeing.

This project aims to build a machine learning model that predicts employee wellness levels using available data, helping HR departments make informed decisions.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on employee wellness data to uncover patterns and trends.
- Clean and preprocess the dataset for effective model training.
- Build and evaluate classification models to predict employee wellness levels.
- Identify key features that impact wellness and mental health at the workplace.

---

## 🎯 Aim

To develop a predictive model that can assess the wellness level of employees based on inputs such as work environment, personal habits, mental health support, and job satisfaction.

---

## 📚 Dataset Description

The dataset includes employee responses related to:

- **Personal Demographics**: `Age`, `Gender`, `Marital Status`
- **Job Details**: `Job Type`, `Department`, `Working Hours`, `Experience`
- **Mental and Physical Health**: `Sleep Quality`, `Physical Activity`, `Stress Levels`, `Support Systems`
- **Target Variable**: `Wellness_Level` (e.g., Low, Medium, High)

---

## 🧪 Exploratory Data Analysis (EDA)

- Distribution analysis of wellness levels across departments and age groups
- Correlation matrix for numeric features
- Countplots and boxplots for categorical vs. target relationships
- Visualized data imbalance (if any)

---

## 🧼 Data Preprocessing

- Handled missing values through imputation
- Label encoded and one-hot encoded categorical variables
- Scaled/normalized numerical features
- Split data into training and testing sets (typically 80/20)

---

## 🤖 Machine Learning Models Used

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **XGBoost Classifier** *(if included)*

---

## ✅ Model Evaluation

Metrics used:

- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, F1-score**
- **ROC-AUC Score**

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~81%     |
| Decision Tree       | ~85%     |
| Random Forest       | **~89%** ✅ |
| SVM                 | ~83%     |
| KNN                 | ~80%     |

🏆 **Best Model**: **Random Forest Classifier** with ~89% accuracy

---

## 📈 Visualizations

- Feature importance from tree-based models
- Heatmap of correlations
- ROC Curves for classification model comparison
- Confusion matrices for each model

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost (optional)

---

## 📁 Project Structure

