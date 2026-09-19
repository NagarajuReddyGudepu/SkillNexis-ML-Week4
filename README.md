# SkillNexis ML & AI Internship – Week 4

## Major Project: Heart Disease Prediction

### Project Overview

This project is developed as part of the SkillNexis Machine Learning & AI Internship – Week 4 Major Project.

The objective is to build a Machine Learning system that predicts whether a patient is likely to have heart disease based on medical features.

## Dataset

- Dataset: Heart Disease UCI Dataset
- Records: 303
- Input Features: 13
- Target: Heart Disease
- Missing Values: None

The dataset was loaded from a GitHub-hosted copy of the Heart Disease UCI dataset.

## Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Feature and Target Separation
4. Train-Test Split
5. Feature Scaling using StandardScaler
6. Logistic Regression
7. Decision Tree
8. Support Vector Machine (SVM)
9. Model Evaluation
10. Cross-Validation
11. GridSearchCV
12. Confusion Matrix
13. ROC Curve
14. Model Saving and Loading
15. Prediction on New Data

## Models Used

### Logistic Regression
- Accuracy: 80.33%
- Precision: 0.77
- Recall: 0.91
- ROC-AUC: 0.87

### Decision Tree
- Accuracy: 70.49%
- Precision: 0.70
- Recall: 0.79

### Support Vector Machine
- Accuracy: 78.69%
- Precision: 0.75
- Recall: 0.91

## Model Optimization

### Cross-Validation

5-fold cross-validation was performed for Logistic Regression.

- Mean CV Accuracy: 82.82%

### GridSearchCV

GridSearchCV was applied to the SVM model.

Best parameters:

- C = 1
- Kernel = Linear

Best CV Accuracy:

- 83.93%

## Model Saving

The trained Logistic Regression model and StandardScaler were saved using Joblib.

Files:

- `heart_disease_model.pkl`
- `heart_disease_scaler.pkl`

The saved model and scaler were successfully loaded and used for prediction.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab
- GitHub

## Project Files

- `SkillNexis_ML_Week4_Heart_Disease_Prediction.ipynb` – Complete project notebook
- `heart_disease_model.pkl` – Trained Logistic Regression model
- `heart_disease_scaler.pkl` – Feature scaler

## Conclusion

This project demonstrates a complete Machine Learning workflow for heart disease prediction, including data preparation, feature scaling, model training, evaluation, optimization, model saving, and prediction.

This project is developed for educational and internship purposes. It is not intended for medical diagnosis.
