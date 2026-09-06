# Thiranex Task 2 — Predictive Modeling Using Machine Learning

## 📌 Project Overview

This project was completed as part of the Thiranex internship Task 2: Predictive Modeling Using Machine Learning.

The objective is to build and compare supervised machine learning models for predicting customer churn using the IBM Telco Customer Churn dataset.

## 🎯 Objective

The project focuses on:

- Preparing and preprocessing customer data
- Handling missing and categorical values
- Splitting data into training and testing sets
- Training multiple classification models
- Evaluating model performance using multiple metrics
- Comparing models using ROC-AUC
- Visualizing performance with a confusion matrix and ROC curves
- Identifying the best-performing model

## 📊 Dataset

The project uses the IBM Telco Customer Churn dataset.

Each row represents a customer and contains information about:

- Customer demographics
- Services subscribed
- Contract information
- Account information
- Monthly and total charges
- Customer churn status

The target variable is **Churn**:

- `No` → 0
- `Yes` → 1

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 🤖 Machine Learning Models

Three classification algorithms were trained and compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

Preprocessing was implemented using Scikit-learn pipelines, including:

- Missing-value imputation
- Feature scaling for numerical features
- One-hot encoding for categorical features

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| **Logistic Regression** | **80.55%** | **65.72%** | **55.88%** | **60.40%** | **0.8419** |
| Random Forest | 80.13% | 66.10% | 51.60% | 57.96% | 0.8387 |
| Decision Tree | 79.13% | 63.42% | 50.53% | 56.25% | 0.8351 |

## 🏆 Best Model

**Logistic Regression** achieved the highest ROC-AUC score of **0.8419** and the highest accuracy of **80.55%** among the evaluated models.

The ROC-AUC comparison shows that Logistic Regression provided the strongest overall class-separation performance for this dataset.

## 📉 Model Evaluation

The project includes:

- Confusion matrix for the best-performing model
- ROC curves for all three models
- ROC-AUC comparison
- Classification metrics
- Random Forest feature importance

The confusion matrix helps evaluate correct and incorrect churn predictions, while the ROC curve shows model performance across different classification thresholds.

## 🔍 Key Findings

- Logistic Regression achieved the best overall performance based on ROC-AUC.
- Logistic Regression achieved an accuracy of **80.55%**.
- Random Forest achieved **80.13% accuracy**.
- Decision Tree achieved **79.13% accuracy**.
- Logistic Regression achieved the highest ROC-AUC of **0.8419**.
- The comparison demonstrates that a more complex model does not necessarily provide the best performance for every dataset.

## 📁 Project File

The complete Jupyter Notebook contains:

- Data loading
- Data inspection
- Data preprocessing
- Exploratory analysis
- Model training
- Model evaluation
- Confusion matrix
- ROC curve comparison
- Feature importance
- Final model comparison
- Key findings and conclusion

## 📚 Reference

Dataset: IBM Telco Customer Churn dataset.

Tutorial concepts referenced for binary classification, confusion matrices, ROC curves, and AUC were adapted to this customer churn prediction problem rather than directly reproducing the tutorial implementation.

## 👨‍💻 Author

Satyam Kumar Singh
