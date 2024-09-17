# Kawasaki-Disease-Machine-Learning
Machine learning models for classifying and predicting Kawasaki disease-related outcomes, including disease differentiation, IVIG resistance prediction, and multi-disease classification

This repository contains machine learning models for classifying and predicting outcomes related to Kawasaki disease. The projects focus on three main tasks: multi-disease classification, distinguishing between typical and atypical Kawasaki disease, and predicting IVIG resistance.

## Projects Overview

### 1. Five-Class Disease Classification

This project classifies five different diseases, including Kawasaki disease, sepsis, and pneumonia, using the CatBoost model. It addresses data imbalance, includes detailed evaluation metrics like PR curves and ROC curves, and uses SHAP for model interpretability.

- [Project Details](Five-Class-Disease-Classification/README.md)

### 2. Kawasaki vs Atypical Kawasaki

This project differentiates between typical Kawasaki disease and atypical Kawasaki disease using an LGBM model with Focal Loss. The key challenge here is class imbalance.

- [Project Details](Kawasaki-Vs-Atypical-Kawasaki/README.md)

### 3. IVIG Resistance Prediction

This project predicts resistance to intravenous immunoglobulin (IVIG) treatment in Kawasaki disease patients. It uses logistic regression and score-based prediction, with a focus on feature selection and model evaluation.

- [Project Details](IVIG-Resistance-Prediction/README.md)

## Repository Structure

```plaintext
Kawasaki-Disease-ML-Models/
│
├── Five-Class-Disease-Classification/
│   ├── data/
│   ├── models/
│   ├── scripts/
│   └── README.md
│
├── Kawasaki-Vs-Atypical-Kawasaki/
│   ├── data/
│   ├── models/
│   ├── scripts/
│   └── README.md
│
├── IVIG-Resistance-Prediction/
│   ├── data/
│   ├── models/
│   ├── scripts/
│   └── README.md
│
└── README.md
