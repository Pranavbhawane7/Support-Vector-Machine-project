# 🧠 Support Vector Machine Project

---

## 📌 Overview
This project applies a **Support Vector Machine (SVM)** classifier to the **Breast Cancer Wisconsin dataset** to predict whether a tumor is **malignant** or **benign**. The dataset contains 30 numerical features describing cell nuclei characteristics extracted from digitized images.

---

## 🎯 Problem Statement
Breast cancer is one of the most common cancers worldwide. Early detection is critical for effective treatment. The aim of this project is to build an SVM model that can accurately classify tumors, demonstrating how machine learning can support medical diagnostics.

---

## 📂 Dataset
- **Source**: Scikit‑learn’s built‑in Breast Cancer dataset  
- **Samples**: 569  
- **Features**: 30 (mean, standard error, and worst values of 10 cell nucleus measurements)  
- **Target**:  
  - `0` → Malignant  
  - `1` → Benign  

---

## ⚙️ Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Checked dataset shape, column info, and target distribution  
   - Verified no missing values  
   - Visualized distributions, boxplots, and correlation heatmaps  

2. **Preprocessing**  
   - Standardized features using `StandardScaler`  
   - Split dataset into training and test sets  

3. **Model Training**  
   - Trained SVM with different kernels (`linear`, `rbf`, `poly`)  
   - Tuned hyperparameters (`C`, `gamma`) using GridSearchCV  

4. **Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1‑score, ROC‑AUC  
   - Confusion matrix and classification report  

---

## 📊 Results
- Achieved accuracy above **95%** with the RBF kernel  
- Features like **mean radius**, **worst area**, and **mean concavity** showed strong separation between malignant and benign classes  

---
