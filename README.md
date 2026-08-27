# Healthcare Disease Prediction Using Machine Learning

## Special Study in ICT

**Topic:** Federated AI Security for Healthcare

### Project Overview

This project demonstrates the application of supervised machine learning algorithms to a healthcare disease classification problem.

The main focus is on **Logistic Regression** and **Support Vector Machine (SVM)** classification. Additional algorithms are also implemented for comparison.

### Dataset

The project uses the **Breast Cancer Wisconsin dataset** available through Scikit-learn.

The dataset contains numerical clinical features and a binary target representing the cancer classification.

### Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall / Sensitivity
* Specificity
* Confusion Matrix

### Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Machine Learning Models
   ↓
Prediction
   ↓
Performance Evaluation
   ↓
Model Comparison
```

### Tools & Technologies

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

### Healthcare Context

Healthcare data can be used with machine learning models to support clinical prediction and decision-making. However, healthcare data is sensitive and distributed across different institutions. Federated Learning provides a potential approach for collaborative model training without centralizing raw patient records.

This project focuses on the **disease prediction/classification component**. Federated Learning and security mechanisms can be considered as a future extension.

### Conclusion

This project demonstrates a complete machine learning classification workflow for a healthcare dataset, from data preprocessing and model training to performance evaluation and comparison.

The results show why multiple evaluation metrics are important for healthcare classification rather than relying only on overall accuracy.
