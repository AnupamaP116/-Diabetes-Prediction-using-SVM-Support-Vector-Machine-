# 🩺 Diabetes Prediction using SVM (Support Vector Machine)

## 📌 Project Overview

This project applies machine learning to predict whether a patient has diabetes using the **Pima Indians Diabetes dataset**. The primary algorithm used is **Support Vector Machine (SVC)**, known for its performance on binary classification tasks.

The goal is to accurately classify patients as diabetic or non-diabetic based on health metrics such as glucose level, BMI, blood pressure, insulin, and more.

---

## 📁 Files in the Repository

- `Diabetes svc.ipynb` – Jupyter Notebook containing all data analysis, model building, and performance evaluation steps
- `README.md` – This project documentation

---

## 📊 Dataset Description

- **Source**: [Kaggle – Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Records**: 768 patients
- **Features**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- **Target**:  
  - `1`: Diabetic  
  - `0`: Non-Diabetic

---

## 🧠 Tech Stack Used

- **Python**
- **Jupyter Notebook**
- **Libraries**:
  - `Pandas`, `NumPy` – For data handling
  - `Matplotlib`, `Seaborn` – For data visualization
  - `Scikit-learn` – For data preprocessing, model building (SVC), and evaluation

---

## 🔍 Workflow Summary

1. **Data Loading & Inspection**  
   - Loaded dataset using Pandas  
   - Checked for missing values and data distribution

2. **EDA (Exploratory Data Analysis)**  
   - Visualized feature distributions and relationships  
   - Analyzed correlations between input features and the target variable

3. **Preprocessing**  
   - Feature scaling using `StandardScaler`  
   - Splitting data into training and test sets (typically 80/20 split)

4. **Model Building**  
   - Used `SVC()` from scikit-learn  
   - Tuned parameters for optimal classification performance

5. **Evaluation Metrics**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report (Precision, Recall, F1-Score)

---

## ✅ Results & Insights

- **Model Used**: Support Vector Classifier (SVC)
- **Best Accuracy Achieved**: *e.g., 78.5%* (replace with your notebook's output)
- **Key Insight**: Glucose level and BMI are strong predictors of diabetes. With proper scaling, SVM performs well for medical classification tasks.

---

## 🚀 How to Run the Project

### 🔧 Requirements

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
