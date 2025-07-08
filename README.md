# 🧠 Machine Learning Models for Classification with SMOTE and Cross-Validation (Python)

This repository contains Python code to train and evaluate multiple machine learning classification models on imbalanced datasets. It uses SMOTE for oversampling the minority class and 5-fold cross-validation for robust model evaluation.

## 🚀 Features

- Handles class imbalance with SMOTE oversampling  
- Uses 5-fold stratified cross-validation  
- Trains and evaluates multiple popular classification models  
- Reports accuracy, confusion matrix, and classification metrics  
- Visualizes cross-validation accuracy comparison  

## 🧪 Models Included

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine  
- Naive Bayes  
- K-Nearest Neighbors  
- XGBoost  
- Multi-Layer Perceptron  
- LightGBM  
- CatBoost  



📊 Output
For each model:

- 5-fold cross-validation accuracy
- Test set accuracy
- Confusion matrix
- Classification report (precision, recall, f1-score)
- Additionally, a bar plot will display cross-validation accuracies for all models for easy comparison.

♻️ Customization
- Easily add or remove models
- Tune hyperparameters inside the script
- Change cross-validation strategy if needed
- Extend to multiclass classification with minor changes

📌 Notes
- SMOTE oversampling is applied only to the training folds to avoid data leakage
- Feature scaling is done to keep data consistent
- All models are trained independently to maintain clarity in evaluation


