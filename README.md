Breast Cancer Classification 
This research uses Machine Learning algorithms to predict the tumor type for breast cancer patients by examining the characteristics of tumor being part of the scikit-learn Breast Cancer Dataset
Dataset:
The dataset is received by the function `sklearn.datasets.load_breast_cancer()`.
It covers 30 features about the tumor like size and shape.
The target variable is `0 = Malignant` and `1 = Benign`.
Model Used:
RandomForestClassifier with 100 decision trees.
The features were standardized by StandardScaler
Results:
Accuracy: ~95% on unknown data was noticed.
Performance Metrics:
Precision, Recall, F1-score within the Classification Report.
Confusion Matrix for harping on a clear conception.


