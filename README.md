# Breast Cancer Analysis

## Project Overview

This project analyzes the Breast Cancer Wisconsin dataset to explore patterns that distinguish benign and malignant tumors.

The analysis combines exploratory data analysis (EDA) with a basic machine learning model to better understand how tumor characteristics relate to malignancy.

---

## Objectives

The main goals of this project are:

- Understand the structure and distribution of the dataset  
- Explore key tumor features such as radius, area, and texture  
- Analyze how these features relate to malignancy  
- Compare benign and malignant tumors  
- Identify important predictive features  
- Build a logistic regression model for classification  
- Evaluate model performance using ROC curve, precision, and recall  

---

## Dataset

The dataset used is the **Breast Cancer Wisconsin Dataset**, available through `scikit-learn`.

It contains:
- 569 observations  
- 30 numerical features describing tumor characteristics  
- A target variable indicating:
  - Malignant (M)
  - Benign (B)

---

## Key Analysis Steps

### 1. Data Exploration
- Class distribution (benign vs malignant)
- Feature ranges and distributions
- Detection of missing values and anomalies

### 2. Feature-Based Analysis
- Comparison of small vs large tumors
- Malignancy rate by tumor size (median split)
- Analysis of radius, texture, and area
- Feature combinations (e.g., radius + area)

### 3. Comparative Analysis
- Differences between benign and malignant tumors
- Correlation analysis
- Identification of redundant features
- Visualization of feature relationships

### 4. Machine Learning
- Logistic Regression model
- Feature scaling
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - ROC Curve (AUC)
- Confusion matrix and error analysis

---

## Key Findings

- Tumor size (radius and area) is strongly associated with malignancy  
- Malignancy rates increase significantly for larger tumors  
- Several geometric features (radius, perimeter, area) are highly correlated  
- Logistic regression achieves strong classification performance  
- ROC analysis shows good separation between benign and malignant tumors  
- Recall is especially important due to the medical context (avoiding false negatives)

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Project Structure
breast-cancer-analysis/
│
├── breast_cancer_analysis.ipynb
├── README.md
└── requirements.txt
