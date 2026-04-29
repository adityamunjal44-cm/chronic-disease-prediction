# Chronic Disease Prediction System

## Overview
This project focuses on building a machine learning model to predict diseases based on patient symptoms using a structured dataset.

## Dataset
- Source: Kaggle
- Training samples: 4920
- Testing samples: 41
- Features: 134 (binary symptom indicators)
- Target: Disease (multi-class classification)

## Approach

### Data Preprocessing
- Used Pandas and NumPy for data handling
- Separated input features and target variable
- Applied StandardScaler to standardize feature values

### Model Training
- Implemented and compared multiple models:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree Classifier
  - Gaussian Naive Bayes

### Model Evaluation
- Evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Used classification report from Scikit-learn for detailed analysis

## Results
- Achieved **97.62% accuracy** on test dataset
- Logistic Regression selected as final model due to stable and consistent performance

## Conclusion
- All models showed comparable performance
- Logistic Regression was preferred due to simplicity, interpretability, and efficiency
- Model evaluated on a separate test dataset to ensure proper generalization

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
