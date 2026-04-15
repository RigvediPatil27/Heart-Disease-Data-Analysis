# Heart-Disease-Data-Analysis

# ❤️ End-to-End Heart Disease Data Analysis & Prediction

## 📌 Project Overview
This project presents a complete end-to-end data analytics and machine learning pipeline on a real-world healthcare dataset to predict the likelihood of heart disease.

It combines data preprocessing, exploratory analysis, statistical insights, and classification models to derive actionable conclusions from patient data.

---

## 🔄 Analytics Pipeline Followed

Problem Definition → Data Collection → Data Cleaning → Exploratory Data Analysis → Feature Engineering → Model Building → Evaluation → Visualization → Insights

---

## 🧠 1. Problem Definition

Heart disease is one of the leading causes of death worldwide.  Early detection using data-driven approaches can significantly improve diagnosis and treatment outcomes.

This project aims to answer:

	•	Can heart disease be predicted using patient attributes?
	•	Which features contribute most to prediction?
	•	What patterns exist in medical indicators?
  •	How do variables like age, cholesterol, and blood pressure affect risk?
  
---

## 🗂️ 2. Dataset Overview

- Source: Kaggle  
- Dataset: Heart Disease UCI Dataset  
- Link: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data  

### 📊 Features:
	•	Age
	•	Sex
	•	Chest Pain Type (cp)
	•	Resting Blood Pressure (trestbps)
	•	Cholesterol (chol)
	•	Maximum Heart Rate (thalach)
	•	Target (0 = No Disease, 1 = Disease)  

---

## 🧹 3. Data Cleaning & Preprocessing (Python)

### Tools Used:
- Python  
- Pandas  
- NumPy  

### Steps Performed:
	•	Removed missing/null values
	•	Eliminated duplicate records
	•	Encoded categorical variables
	•	Outlier detection using Z-score
	•	Feature scaling (if applied)
  
---

## 📊 4. Exploratory Data Analysis (EDA)

### Tools:
- Matplotlib  
- Seaborn  

### Key Findings:
	•	Strong correlation between chest pain type and heart disease
	•	Higher cholesterol levels are associated with increased risk
	•	Maximum heart rate (thalach) shows inverse relation with disease
	•	Age shows a gradual increase in disease probability 
  •	Some features show clear correlation with target variable

---

## 🤖 5. Model Building

### Models Used:
	•	Logistic Regression
	•	Decision Tree Classifier 

### Why:
	•	Logistic Regression: Baseline linear classification model
	•	Decision Tree: Captures non-linear relationships and feature interactions 

---

## 📈 6. Model Evaluation

### Metrics Used:
	•	Accuracy
	•	Precision
	•	Recall
	•	F1 Score
	•	Confusion Matrix

### Results:
	•	Logistic Regression Accuracy:  0.8043478260869565
	•	Decision Tree Accuracy: 0.7663043478260869
👉 Best Model: (update after running)

---

## 📊 7. Visualization & Dashboard

Tools:
- Power BI / Matplotlib  

Dashboard includes:
	•	Distribution of patients by age & gender
	•	Feature-wise risk comparison
	•	Correlation heatmap
	•	Model prediction insights
  
---

## 🔍 8. Key Insights

	•	Chest pain type is one of the strongest predictors
	•	Patients with higher cholesterol show elevated risk
	•	Lower maximum heart rate is linked to higher disease probability
	•	Age positively correlates with heart disease occurrence
	•	Some features exhibit non-linear relationships, justifying tree-based models
	•	High cholesterol increases heart disease risk 
	• Older age groups are more vulnerable
	•	Certain medical indicators strongly influence prediction 

---

## 🎯 9. Limitations
	•	Dataset size is relatively small
	•	Limited feature diversity (no lifestyle/genetic data)
	•	Possible overfitting in Decision Tree
	•	Model may not generalize well to real-world populations

---

## 🎯 10. Future Improvements
	•	Use advanced models (Random Forest, XGBoost)
	•	Perform hyperparameter tuning
	•	Deploy as a web application
	•	Integrate real-time healthcare data
	•	Add feature importance explainability (SHAP, LIME)
---

## 🎯 11. Key Learnings

	•	Data preprocessing significantly impacts model performance
	•	EDA helps uncover hidden patterns before modeling
	•	Simpler models can perform competitively
	•	Visualization enhances interpretability of results

---

## 📂 Repository Structure

project/
│── data/
│── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── EDA.ipynb
│   ├── modeling.ipynb
│── outputs/
│── dashboard.pbix
│── README.md

---

## ▶️ How to Run

1.	Open notebooks in Jupyter/Google Colab
	2.	Run in sequence:
	•	Data Preprocessing
	•	EDA
	•	Modeling
	3.	Open Power BI dashboard (.pbix) for visualization
---
