# Breast Cancer Prediction using SVM (Scikit-learn)

## Goal
Build a classification model to predict malignant vs benign tumors using the Breast Cancer Wisconsin dataset.

## Dataset
- Source: sklearn.datasets.load_breast_cancer

## Approach
1. Data loading and quick EDA
2. Train-test split
3. Feature scaling (StandardScaler)
4. Model training (SVM)
5. Hyperparameter tuning (GridSearchCV for C and gamma, kernel=rbf)
6. Evaluation (accuracy, confusion matrix and classification report)

## Results
- Best params: C= 1, gamma= 1
- Test accuracy: 97%

## How to run
```bash
pip install -r requirements.txt
jupyter notebook
