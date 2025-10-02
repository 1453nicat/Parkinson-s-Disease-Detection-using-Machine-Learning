# Parkinson-s-Disease-Detection-using-Machine-Learning

This project implements a machine learning pipeline to detect Parkinson's Disease (PD) using voice measurement data from the UCI Machine Learning Repository. The dataset includes 195 samples with 23 biomedical voice features, where the target variable indicates PD status (0 for healthy, 1 for PD). The project uses Logistic Regression, Random Forest, and SVM classifiers, with hyperparameter tuning via GridSearchCV to optimize performance.

### Project Overview
The goal of this project is to build and evaluate machine learning models to accurately classify individuals as having Parkinson's Disease or being healthy based on voice features. The pipeline includes, such as data preprocessing (scaling, train-test split), Exploratory Data Analysis (EDA) with correlation heatmaps., model training with Logistic Regression, Random Forest, and SVM, hyperparameter tuning using GridSearchCV, evaluation using accuracy, precision, recall, and F1-score. Also, the project is implemented in a Google Colab notebook, making it easy to run and reproduce.

Furthermore, the dataset is sourced from the UCI Parkinson's Dataset. It contains:

- 195 samples: 147 PD patients, 48 healthy individuals.
- 23 features: Vocal frequency measures (e.g., jitter, shimmer, HNR).
- Target: Binary classification (0 = healthy, 1 = PD).

### Results

1) Random Forest (Tuned):

Accuracy: 0.92
Precision: 0.9394
Recall: 0.9688
F1-Score: 0.9538

2) SVM (Tuned):

Accuracy: 0.92
Precision: 0.9143
Recall: 1.0000
F1-Score: 0.9552

3) Logistic Regression (Tuned):

Accuracy: 0.90
Precision: 0.8889
Recall: 1.0000
F1-Score: 0.9412

In conclusion, Random Forest (Tuned) is recommended for its balanced precision and recall, while SVM (Tuned) excels in scenarios requiring perfect recall (no missed PD cases). See the notebook for detailed confusion matrices and feature importance.

MIT License Copyright (c) 2025 *1453nicat*
