# Advanced Heart Disease Prediction System

An AI-powered healthcare prediction system designed to analyze patient medical data and predict the risk of heart disease using advanced Machine Learning and Explainable AI techniques.

This project was developed to improve prediction accuracy, reduce overfitting, optimize clinical decision thresholds, and provide interpretable results for healthcare-related analysis.

---

# Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction and risk assessment can help in preventive healthcare and faster medical intervention.

This project uses multiple Machine Learning techniques, ensemble learning models, feature engineering, calibration methods, and explainable AI to build a robust heart disease prediction system.

The system analyzes important medical parameters such as:
- Age
- Cholesterol
- Blood Pressure
- Maximum Heart Rate
- Exercise-induced Angina
- ECG results
- Chest pain type
- ST depression
- Fasting blood sugar
- Other clinical attributes

and predicts the probability of heart disease risk.

---

# Machine Learning Pipeline

## 1. Data Collection
The heart disease dataset was collected from publicly available healthcare datasets such as:
- UCI Heart Disease Dataset
- Kaggle Healthcare Datasets

---

## 2. Data Preprocessing
The raw medical dataset was cleaned and prepared using:
- Missing value handling
- Median imputation
- Categorical encoding
- Robust scaling
- Feature normalization

A preprocessing pipeline was built using:
- Scikit-learn Pipelines
- ColumnTransformer

---

## 3. Feature Engineering
Advanced medically-inspired features were created to improve model learning and clinical relevance.

Engineered features include:
- Age / Heart Rate ratio
- Heart Rate reserve
- Blood Pressure × Age interaction
- Cholesterol / Age ratio
- Oldpeak and ST slope interactions
- Angina severity combinations

These features helped improve model performance and generalization.

---

# Models Used

## Primary Model
- CatBoost Classifier

## Ensemble Models
- XGBoost
- LightGBM
- Stacking Ensemble Learning

The final system combines multiple models to improve:
- Accuracy
- Stability
- Generalization
- Clinical reliability

---

# Overfitting Reduction Techniques

Several anti-overfitting strategies were implemented:

- Reduced tree depth
- L2 regularization
- Subsampling
- Column sampling
- Minimum leaf constraints
- Cross-validation
- Probability calibration
- Threshold optimization

These techniques significantly improved validation performance and model robustness.

---

# Hyperparameter Optimization

The project uses:
- Optuna Hyperparameter Tuning

to automatically search for the best model parameters for:
- Learning rate
- Tree depth
- Regularization
- Sampling ratios
- Iterations

---

# Explainable AI (XAI)

The system integrates SHAP (SHapley Additive Explanations) for explainability.

SHAP helps visualize:
- Important medical features
- Feature impact on predictions
- Model decision behavior

This improves transparency and trust in healthcare AI systems.

---

# Clinical Threshold Optimization

Instead of using a default 0.5 prediction threshold, the project optimizes thresholds using:
- F1 Score
- Recall
- Youden Index

This allows better balance between:
- Sensitivity
- Specificity
- Precision

which is critical in medical diagnosis systems.

---

# Evaluation Metrics

The model was evaluated using:
- ROC-AUC Score
- Accuracy
- Precision
- Recall
- F1 Score
- Specificity
- Cross-validation metrics
- Confusion Matrix

---

# Technologies Used

## Programming Language
- Python

## Libraries & Frameworks
- Scikit-learn
- CatBoost
- XGBoost
- LightGBM
- SHAP
- Optuna
- Pandas
- NumPy
- Matplotlib

---

# Features

- Advanced Heart Disease Prediction
- Ensemble Learning
- Explainable AI
- Clinical Risk Analysis
- Feature Engineering
- Threshold Optimization
- Probability Calibration
- Cross-Validated Evaluation
- Anti-Overfitting Pipeline

---

# Future Improvements

- Deep Learning integration
- Real-time patient monitoring
- Web application deployment
- Multi-disease prediction system
- IoT healthcare integration
- Cloud deployment
- AI medical assistant integration

---

# Conclusion

This project demonstrates how advanced Machine Learning, ensemble models, and explainable AI can be combined to create a more reliable and clinically meaningful heart disease prediction system.

The pipeline focuses not only on accuracy, but also on:
- robustness,
- interpretability,
- calibration,
- and real-world healthcare applicability.
