
# Diabetes Patients Early Readmissions Prediction
---

## 📌 Project Overview

This project aims to predict **early readmission** of diabetes patients using machine learning models trained on real-world hospital data. The goal is to classify whether a patient will be readmitted within 30 days after discharge. Predicting early readmission can help healthcare providers reduce costs and improve patient care.

---

## 📁 Repository Structure

```
dataset/
│
├── Data Dictionary.png           # Schema reference
├── diabetic_data.csv             # Main dataset
├── IDs_mapping.xls               # Attribute mappings
Diabetic_Patient_Re_admission_Prediction.ipynb  # Project notebook
requirements.txt              # Required packages
readme.md                     # Project documentation (this file)
```

---

## 📊 Dataset

We used the **Diabetes 130-US hospitals for years 1999–2008** dataset.

> The dataset represents 10 years (1999–2008) of clinical care at 130 US hospitals. It includes over 50 features representing patient demographics, clinical lab results, hospital encounters, medications, and health outcomes.

### Dataset Criteria:
- Inpatient encounters only
- Diabetes diagnosis present
- Stay duration: 1–14 days
- Lab tests and medications recorded

📎 [UCI Repository](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)  
📎 [Original Paper (Supplementary Materials)](https://academic.oup.com/jamia/article/21/2/263/703218)

---

## ⚙️ Installation & Setup

### Prerequisites

- Python ≥ 3.8
- Jupyter Lab / Notebook

### Install Dependencies

**Option 1 – From the terminal**  
Run this from the project root directory:

```bash
pip install -r requirements.txt
```

**Option 2 – From the notebook**  
In the Jupyter Notebook, a cell is included that automatically installs dependencies:
```python
!pip install -r requirements.txt
```

> ⚠️ Ensure all dataset files are placed in the `dataset/` folder.
---

## 🚀 How to Run

Open the notebook using Jupyter:

```bash
jupyter notebook dataset/Diabetic_Patient_Re_admission_Prediction.ipynb
```

Follow the structured notebook steps to:
- Explore and preprocess the dataset
- Train machine learning models
- Evaluate using performance metrics
- Analyze top features

---

## 🤖 Models Implemented

- Logistic Regression  
- CatBoost Classifier  
- k-Nearest Neighbors
- Gaussian Naive Bayes

Each model is trained and evaluated on:
- Imbalanced dataset  
- Undersampled dataset  
- Oversampled dataset

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

Confusion matrices and ROC curves are included for interpretation.

---
