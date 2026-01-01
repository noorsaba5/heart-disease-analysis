# Predicting Heart Disease Using Statistical Analysis and Machine Learning
# Project Overview

This project presents an end-to-end applied data science analysis to identify key risk factors associated with heart disease and to build predictive models that support early risk assessment.

Using real clinical data from patients evaluated at the Cleveland Clinic Foundation, the project integrates exploratory data analysis, statistical hypothesis testing, and machine learning to generate reliable, interpretable, and actionable insights in a healthcare context.

# Objectives

Analyze clinical patient data to understand heart disease risk factors

Validate assumptions using statistical hypothesis testing

Build and compare predictive machine learning models

Translate analytical results into decision-ready insights

# Dataset

Source: UCI Machine Learning Repository (Heart Disease – Cleveland dataset)

Records: 297 patients (after cleaning)

Features: 13 clinical attributes

Target Variable:

0 → No heart disease

1 → Presence of heart disease

# Dataset file used:

data/processed.cleveland.data

# Methodology
# Data Preparation

Handling missing values encoded as ?

Type conversion and data validation

Binary target transformation

# Exploratory Data Analysis (EDA)

Distribution analysis of key clinical features

Comparative analysis between diseased and non-diseased patients

Correlation analysis to identify relationships

# Hypothesis Testing

Independent t-tests

Chi-square tests of independence

Mann–Whitney U tests

Statistical testing confirmed several clinically relevant assumptions.

# Predictive Modeling

Two models were developed and evaluated:

# Logistic Regression

High interpretability

Odds ratios used to explain feature influence

# Random Forest

Captures nonlinear relationships

Achieved superior predictive performance

# Evaluation Metrics

Accuracy

ROC-AUC

Confusion Matrix

# Key Findings

Age, chest pain type, ST depression during exercise, and exercise capacity are strong predictors of heart disease

Statistical findings and machine learning feature importance were highly consistent

Random Forest provided the best overall predictive performance

# Practical Implications

Supports early identification of high-risk patients

Demonstrates how machine learning can complement traditional clinical analysis

Highlights the value of combining interpretability with predictive power in healthcare analytics

# Limitations & Future Work

Dataset size is relatively small

Data sourced from a single primary cohort

Future work may include external validation and additional clinical features

# Repository Structure
heart-disease-analysis/
├── notebook/
│   └── Heart_Disease_Analysis.ipynb
├── data/
│   └── processed.cleveland.data
├── outputs/
│   └── poster/
├── slides/
├── README.md
├── requirements.txt
└── .gitignore

# How to Run the Project

Clone the repository:

git clone https://github.com/noorsaba5/heart-disease-analysis.git


Install dependencies:

pip install -r requirements.txt


Open and run the notebook:

notebook/Heart_Disease_Analysis.ipynb

# Acknowledgements

UCI Machine Learning Repository

Cleveland Clinic Foundation

Codecademy — Applied Data Science with Python Bootcamp

# Author

# Noor Saba
Applied Data Science & Machine Learning Enthusiast
