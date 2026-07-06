# Breast Cancer Classification using Support Vector Machines (SVM)

An end-to-end machine learning project that applies Support Vector Machines (SVM) to classify breast cancer tumors using the Breast Cancer Wisconsin Diagnostic Dataset. This project explores different SVM kernels, performs hyperparameter tuning with Grid Search, analyzes model performance, and investigates the impact of noisy and overlapping data.

---

## Project Overview

Support Vector Machines (SVM) are powerful supervised learning algorithms widely used for classification tasks. In this project, different SVM kernels are implemented and compared to classify breast cancer tumors as either **Benign** or **Malignant**.

The project covers the complete machine learning workflow, from preprocessing and visualization to model evaluation and performance analysis.

---

## Features

- Data preprocessing
- Label encoding
- Feature scaling using StandardScaler
- Exploratory Data Analysis (EDA)
- Feature selection using correlation analysis
- Linear SVM
- RBF SVM
- Polynomial SVM
- Decision boundary visualization
- Kernel comparison
- Hyperparameter tuning using Grid Search
- Training and prediction time analysis
- Overlapping classes experiment
- Gaussian noise experiment

---

## Dataset

This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset** from the UCI Machine Learning Repository.

- Samples: 569
- Features: 30 numerical features
- Target Classes:
  - Malignant (M)
  - Benign (B)

Dataset source: UCI Machine Learning Repository – Breast Cancer Wisconsin (Diagnostic) Dataset

**Dataset:** Breast Cancer Wisconsin Diagnostic Dataset

- 569 samples
- 30 numerical features
- Binary classification
  - Malignant (M)
  - Benign (B)

---

## Project Structure

```
breast-cancer-svm-classification/
│
├── SVM.ipynb
├── README.md
├── requirements.txt
├── dataset/
└── images/
```

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Workflow

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Model Training
6. Kernel Comparison
7. Hyperparameter Tuning
8. Performance Analysis
9. Noise Analysis
10. Overlapping Classes Analysis
11. Conclusions

---

## Results

The project compares:

- Linear Kernel
- RBF Kernel
- Polynomial Kernel

using:

- Validation Accuracy
- Testing Accuracy
- Training Time
- Prediction Time

The effect of noisy and overlapping data is also analyzed to evaluate the robustness of SVM.

---

## Future Improvements

- Cross Validation
- ROC Curve
- Precision-Recall Curve
- Learning Curves
- Streamlit Deployment

---

## Author

**Rewan Khaled**

Artificial Intelligence Student | Machine Learning Enthusiast
