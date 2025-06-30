# 🩺 Diabetes Prediction Using Machine Learning

This project uses a medical dataset from the **National Institute of Diabetes and Digestive and Kidney Diseases** to build a classification model that predicts the likelihood of an individual developing diabetes.

## 📘 Project Overview

The goal is to develop a machine learning model that can assess the risk of diabetes based on a range of diagnostic measurements. The model can be used as a preliminary screening tool to aid healthcare providers in identifying high-risk individuals.

## 🎯 Objective

To build a **binary classification model** that can predict whether an individual is likely to develop diabetes within the next 5 years.

## 📊 Dataset Description

The dataset includes several medical predictor variables (features) and one target variable (Outcome):

### 🔹 Features (Independent Variables):

- **Pregnancies** – Number of times pregnant  
- **Glucose** – Plasma glucose concentration (2 hours in an oral glucose tolerance test)  
- **BloodPressure** – Diastolic blood pressure (mm Hg)  
- **SkinThickness** – Triceps skinfold thickness (mm)  
- **Insulin** – 2-Hour serum insulin (mu U/ml)  
- **BMI** – Body mass index (weight in kg/(height in m)^2)  
- **DiabetesPedigreeFunction** – Diabetes pedigree function  
- **Age** – Age (years)  

### 🎯 Target (Dependent Variable):

- **Outcome** – Class variable (0: No diabetes, 1: Diabetes)

## ✅ Key Features

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Model training with algorithms like Logistic Regression, Random Forest, and SVM  
- Evaluation using accuracy, confusion matrix, ROC curve, and more  
- Hyperparameter tuning for optimal performance

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## 📈 Model Evaluation

- Confusion Matrix

- Accuracy, Precision, Recall, F1-score

- ROC Curve and AUC

## 📊 Results

| Model            | Accuracy |
|------------------|----------|
| Logistic Regression  | 81.1%    |
| Random Forest     | 80.5%   |
| Decision Tree    | 79.2%    |
| KNN       | 79.2% |
| Naïve Bayes              | 78.5%    |
| SVM              | 77.2%    |

> 🔍 Logistic Regression model outperformed other classifiers in both accuracy and generalization.

## 💡 Future Work

- Deploy the model using Flask or Streamlit

- Integrate with a frontend for real-time predictions

- Explore deep learning approaches for improved accuracy

- Handle missing values and outliers more robustly


## 🙌 Acknowledgments

- National Institute of Diabetes and Digestive and Kidney Diseases for the dataset

- The open-source ML and data science community



