# 🩺 Diabetes Detection Using Machine Learning

This project aims to detect the presence of diabetes in patients using a supervised machine learning model. The dataset is derived from the Pima Indians Diabetes Dataset, which includes medical diagnostic data. The objective is to predict whether a patient has diabetes based on features such as glucose level, BMI, age, insulin, and more.

## 🔍 Project Overview

- **Problem**: Automatically detect diabetes based on patient diagnostic data.
- **Approach**: A machine learning classification pipeline using data preprocessing, EDA, and model training/evaluation.
- **Model**: Logistic Regression (can be replaced/compared with other classifiers).

## 📁 Dataset

The dataset includes the following features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target Variable: 1 for diabetic, 0 for non-diabetic)

## 📊 Technologies Used

- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 🧠 Machine Learning Workflow

1. **Data Cleaning & Preprocessing**
   - Replacing invalid values (`0`) with `NaN` in features like Glucose, BMI, etc.
   - Handling missing values with imputation.

2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and correlations among features.
   - Heatmaps and boxplots to identify patterns and outliers.

3. **Feature Selection & Splitting**
   - Splitting data into training and testing sets.

4. **Model Training**
   - Using Logistic Regression for binary classification.

5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

## 📈 Results

- Model achieves reasonable accuracy in predicting diabetes based on the features.
- Evaluation metrics indicate balanced performance on both classes (diabetic and non-diabetic).
