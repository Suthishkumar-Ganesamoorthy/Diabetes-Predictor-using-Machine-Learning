# Diabetes-Predictor-using-Machine-Learning

# 🩺 Diabetes Predictor – Machine Learning Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MzgbB6rFap32UaIl9Cq6sH0XBpajAtLz)

---

## 📌 Overview
This project predicts whether a person is diabetic or not using **Machine Learning models** on the **Pima Indians Diabetes Dataset**.  
The dataset consists of diagnostic measurements of females aged ≥ 21 years.  

Dataset link: [Diabetes CSV (Plotly Datasets)](https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv)

---

## 📂 Dataset Details

| Feature                    | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `Pregnancies`               | Number of times pregnant                                                    |
| `Glucose`                   | Plasma glucose concentration (mg/dL)                                        |
| `BloodPressure`             | Diastolic blood pressure (mm Hg)                                            |
| `SkinThickness`             | Triceps skinfold thickness (mm)                                             |
| `Insulin`                   | 2-hour serum insulin (µU/mL)                                                |
| `BMI`                       | Body mass index (kg/m²)                                                     |
| `DiabetesPedigreeFunction`  | Diabetes risk score based on family history                                 |
| `Age`                       | Age of the patient (years)                                                  |
| `Outcome` (target)          | 1 = Diabetic, 0 = Non-diabetic                                              |

---

## ⚙️ Workflow

1. **Data Preprocessing**  
   - Handle missing or zero values in medical features  
   - Feature scaling for uniformity  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizations of feature distributions  
   - Correlation heatmap  

3. **Model Training**  
   - Logistic Regression  
   - Random Forest  
   - Support Vector Machine (SVM)  
   - K-Nearest Neighbors (KNN)  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  
   - ROC-AUC  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  
