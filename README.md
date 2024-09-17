# Kawasaki-Disease-Machine-Learning
Machine learning models for classifying and predicting Kawasaki disease-related outcomes, including disease differentiation, IVIG resistance prediction, and multi-disease classification

## Projects Overview

### 1. Five-Class Disease Classification

This project classifies five different diseases, including Kawasaki disease, sepsis, and pneumonia, using the CatBoost model. It addresses data imbalance, includes detailed evaluation metrics like Precision-Recall (PR) curves and Receiver Operating Characteristic (ROC) curves, and uses SHAP for model interpretability.

- **Goal**: To classify patients into one of five disease categories.
- **Key Models**: CatBoost, LightGBM, XGBoost.
- **Features**: Blood markers, clinical features like temperature, and other relevant clinical data.
- **Evaluation**: Confusion matrix, PR curve, ROC curve, and SHAP analysis.

[Detailed Instructions for Five-Class Classification](Five-Class-Disease-Classification/README.md)

### 2. Kawasaki vs Atypical Kawasaki Classification

This project focuses on distinguishing between typical Kawasaki disease and atypical Kawasaki disease using the LightGBM model with Focal Loss. This model addresses significant class imbalance issues.

- **Goal**: To differentiate between typical and atypical Kawasaki disease.
- **Key Models**: LightGBM with Focal Loss.
- **Challenges**: Class imbalance (small number of atypical Kawasaki cases).
- **Evaluation**: Confusion matrix, ROC curve, sensitivity, and specificity.

[Detailed Instructions for Kawasaki vs Atypical Classification](Kawasaki-Vs-Atypical-Kawasaki/README.md)

### 3. IVIG Resistance Prediction

This project predicts resistance to intravenous immunoglobulin (IVIG) treatment in Kawasaki disease patients using logistic regression and a score-based system. Various feature selection techniques such as LASSO and Mann-Whitney U tests are applied.

- **Goal**: To predict whether patients will respond to IVIG treatment.
- **Key Models**: Logistic regression, score-based system.
- **Features**: Clinical and lab results, patient demographics.
- **Evaluation**: Sensitivity, specificity, ROC curve.

[Detailed Instructions for IVIG Resistance Prediction](IVIG-Resistance-Prediction/README.md)
