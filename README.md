## Bank Marketing Dataset – ML Model Comparison
This project applies various machine learning models on the Bank Marketing dataset to predict whether a client subscribes to a term deposit. The goal is to compare core ML models on a real-world dataset and observe the impact of preprocessing, feature selection, and regularization.


### Objective
Binary classification (target: 0 = no, 1 = yes) using both regression and classification techniques.

### Dataset
Source: OpenML
Rows: ~45,000
Features: mix of categorical & numerical
Target: target (binary)

### Workflow
Data Cleaning & Encoding
Ordinal + One-hot encoding
Removal of low-correlation and high-correlation features

### Modeling Approaches

Linear Regression
Logistic Regression (none, l1, l2)
Ridge & Lasso Regularization
Decision Tree
Random Forest
XGBoost


### Evaluation

StratifiedKFold Cross Validation
Metrics: RMSE (regression), Accuracy & R² (classification)

### Tools
Python · scikit-learn · XGBoost · OpenML · pandas 

