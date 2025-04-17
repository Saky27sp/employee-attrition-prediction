# 🧠 Employee Attrition Prediction

This project applies predictive analytics and machine learning to forecast employee attrition using HR data. It aims to assist organizations in identifying at-risk employees and improve retention strategies.

---

## 📌 Project Structure

- `data/`: Contains the dataset (`Employee-Attrition.csv`)
- `notebooks/`: Jupyter notebook for full code implementation
- `reports/`: Project report and IEEE-format base research paper
- `outputs/`: Confusion matrices, ROC curves, feature importance plots
- `README.md`: Project overview and instructions
- `requirements.txt`: Python dependencies

---

## 📊 Problem Statement

> Predict which employees are likely to leave the company based on historical HR data.

---

## 🎯 Objectives

- Explore the dataset and understand key attrition trends
- Preprocess data and encode categorical variables
- Train models (Logistic Regression, Decision Tree, Random Forest, SVM)
- Evaluate models using accuracy, precision, recall, ROC-AUC
- Visualize feature importance and correlation

---

## 📁 Dataset Info

- Source: IBM HR Analytics
- Records: 1470 employees
- Target variable: `Attrition` (Yes/No)
- Features include: Age, MonthlyIncome, JobRole, OverTime, etc.

---

## 🧪 Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 📈 Visuals

All visual outputs (confusion matrix, ROC curve, feature importance) are saved in the `outputs/` folder. These are referenced in the report and IEEE paper.

---

## 📜 Reports

- `Employee_Attrition_Report.docx`: Full report with problem statement, methodology, evaluation, and future scope
- `Employee_Attrition_Paper.docx`: IEEE-style formatted base paper (2-column academic style)

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/employee-attrition-prediction.git
   cd employee-attrition-prediction
