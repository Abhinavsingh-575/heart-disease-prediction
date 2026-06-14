# Heart Disease Prediction System

## Overview
An end-to-end Machine Learning project that predicts 
the presence of heart disease in patients using 
real clinical data from 4 countries.

## Business Problem
Every year millions of people die due to undetected 
heart disease. This model helps doctors identify 
high-risk patients early using clinical parameters.

## Dataset
- Source: Heart Disease UCI Multi-Country Dataset
- Records: 920 real patient records
- Countries: USA, Hungary, Switzerland, Cleveland
- Features: 15 clinical features

## Project Steps
| Step | Description |
|------|-------------|
| EDA | Explored patterns in age, cholesterol, BP |
| Feature Engineering | Created age groups, BP categories, risk score |
| Data Cleaning | Handled missing values and outliers |
| Model Training | Trained 3 ML models |
| Evaluation | Compared models using ROC-AUC and F1 Score |

## Results
| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 82% | 0.82 |
| Random Forest | 83% | 0.83 |
| XGBoost | 86% | 0.86 |

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost, Seaborn, Matplotlib

## Project Structure
heart_disease_project/
├── data/
│   └── heart_disease_uci.csv
├── notebooks/
│   └── project.ipynb
└── README.md

## How to Run
git clone https://github.com/Abhinavsingh-575/heart-disease-prediction.git
cd heart-disease-prediction
jupyter notebook notebooks/project.ipynb

## Author
Abhinav Singh
GitHub: https://github.com/Abhinavsingh-575
