## STT810 Project: Automated Diagnosis of Cancer Cells using Supervised Machine Learning

### Project Overview
This project focuses on the application of supervised machine learning techniques to classify breast cancer cells as benign or malignant based on features extracted from the Wisconsin Breast Cancer dataset. The goal is to compare multiple classification models, evaluate their performance, and identify the most effective model for automated cancer cell diagnosis.

---

### Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Features: 30 numeric features describing cell properties (e.g., radius, texture, smoothness)
- Target Classes:
  - 0 = benign
  - 1 = malignant

> The target class has been remapped to align with standard clinical interpretation, where malignant cases are treated as the positive class.

---

### Models Used
1. Logistic Regression
2. Random Forest Classifier
3. Support Vector Classifier (RBF kernel)
4. Naive Bayes Classifier

---

### Evaluation Metrics
The models are evaluated using the following metrics:

- Accuracy: Proportion of all correctly classified samples.  
- Precision: Proportion of predicted malignant samples that are truly malignant. High precision reduces false positives.  
- Recall (Sensitivity): Proportion of actual malignant samples correctly identified. High recall reduces false negatives.  
- F1 Score: Harmonic mean of precision and recall, balancing false positives and false negatives.