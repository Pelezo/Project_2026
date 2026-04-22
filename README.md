# Project_2026
This repository contains my 2026 project

# Smoking Status Prediction Using Bio-Signal Data
Project Overview
This project focuses on analyzing bio-signal and clinical health data to identify and predict the smoking status of individuals. The analysis combines exploratory data analysis (EDA), statistical hypothesis testing, and machine learning techniques to understand how smoking affects physiological and biomedical features.
The goal is to build an objective, data-driven approach to smoking status classification using routinely collected health indicators.

# Dataset Description
The dataset contains demographic, physical, clinical, and laboratory features, including:

Demographics: age, gender
Body measurements: height, weight, waist circumference
Vital signs: systolic and diastolic (relaxation) blood pressure
Sensory data: eyesight (left/right), hearing (left/right)
Blood tests: cholesterol, triglycerides, HDL, LDL, fasting blood sugar, hemoglobin
Organ function markers: AST, ALT, γ-GTP, serum creatinine
Urine protein levels
Oral and dental health indicators
Target variable: smoking status


# Exploratory Data Analysis (EDA)

Distribution plots for numerical features
Comparison of smokers vs non-smokers
Identification of skewness, outliers, and class imbalance
Visualization of key health indicators affected by smoking


# Statistical Analysis
Statistical hypothesis testing (t-tests) was performed to evaluate differences between smokers and non-smokers.
Significant differences were observed in features such as:

Age
Hemoglobin
Cholesterol
Systolic blood pressure
Fasting blood sugar

These results indicate a strong association between smoking behavior and multiple physiological measurements.

# Machine Learning Models
The following models were trained and evaluated:

Logistic Regression
Random Forest

To address class imbalance, SMOTE (Synthetic Minority Over-sampling Technique) was applied.
Evaluation Metrics

Accuracy
Precision
Recall
F1-score
ROC-AUC

Model performance was compared before and after applying SMOTE, showing improved recall and ROC-AUC scores after balancing the dataset.

# Key Insights

Smoking has measurable effects on cardiovascular, metabolic, and blood-related health indicators.
Statistical analysis confirms significant differences between smoking and non-smoking groups.
Random Forest models generally outperform Logistic Regression.
SMOTE improves performance when handling imbalanced classes.


# Technologies Used

Python
pandas, numpy
matplotlib, seaborn
scikit-learn
imbalanced-learn (SMOTE)


# Project Structure
Data From kaggle 
https://www.kaggle.com/datasets/kukuroo3/body-signal-of-smoking
Notebook
Smoker status evaluation.ipynb
README.md

# Conclusion
This project demonstrates how bio-signal and health data can be used to objectively assess smoking status. Such approaches can support preventive healthcare, public health research, and non-invasive health monitoring systems.

