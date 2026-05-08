# -Machine-Learning-Based-Predictive-Analytics-for-Patient-Disposition
# 🏥 Machine Learning-Based Predictive Analytics for Patient Disposition

## 📌 Internship Project Report  
**Organization:** GEOPIC, ONGC, Dehradun  
**University:** Graphic Era (Deemed to be University), Dehradun  
**Program:** MBA (AI & Data Science)  
**Session:** 2024–2026  

---

## 🎯 Project Title  
**Machine Learning-Based Predictive Analytics for Patient Disposition**

---

## 📌 Business Problem

Healthcare institutions generate large volumes of patient data through electronic health records, laboratory tests, and monitoring systems. However, this data is often underutilized in decision-making.

Hospitals face key challenges such as:

- Delayed identification of critical patients  
- Inefficient allocation of ICU beds and resources  
- Lack of early prediction of patient outcomes  
- Manual decision-making leading to inconsistency  

There is a need for an intelligent system that can **predict patient disposition (Admitted, Discharged, or Deceased)** using clinical and physiological data.

---

## 🎯 Objective

The objective of this project is to develop a machine learning-based predictive system that:

- Predicts patient outcomes using clinical parameters  
- Supports early risk identification  
- Enhances hospital decision-making efficiency  
- Improves resource allocation and patient care  
- Demonstrates application of AI in healthcare analytics  

---

## 📊 Dataset Description

- **Total Records:** 289 patients  
- **Features:** 29 clinical and physiological attributes  
- **Target Variable:** Patient Disposition (Admitted / Discharged / Deceased)  

### Key Feature Categories:

**1. Vital Signs**
- Respiratory Rate (RR)  
- Oxygen Saturation (SpO2)  
- FiO2  
- Heart Rate  
- Mean Arterial Pressure (MAP)  

**2. Laboratory Indicators**
- pH Level  
- PO2 / PCO2  
- HCO3  
- Lactate  

**3. Diagnostic Scores**
- POCUS Score  
- CRP  
- SO2/FiO2 Ratio  

---

## ⚙️ Methodology

The project followed a structured data science pipeline:

### 1. Data Preprocessing
- Missing value treatment (mean/median/mode imputation)  
- Removal of irrelevant columns  
- Encoding categorical variables  
- Feature scaling and normalization  

### 2. Exploratory Data Analysis (EDA)
- Trend analysis of clinical variables  
- Correlation analysis  
- Class distribution study  

### 3. Feature Selection
- Correlation matrix analysis  
- Feature importance ranking  
- Domain-driven feature filtering  

### 4. Model Development
Multiple machine learning models were implemented:

- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  
- Gradient Boosting Classifier  

---

## 🤖 Model Evaluation

Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

### Best Performing Model:
- **Gradient Boosting Classifier**

### Performance Improvement:
- Before tuning: ~0.8998  
- After tuning (GridSearchCV + Bayesian Optimization): ~0.9170  

---

## 🛠️ Tools & Technologies Used

- Microsoft Excel – Data preparation  
- Python – Data analysis & modeling  
- Pandas, NumPy – Data processing  
- Scikit-learn – Machine learning models  
- Matplotlib, Seaborn – Data visualization  
- SQL – Data querying & extraction  

---

## 📌 Key Insights

- Oxygen saturation (SpO2) and respiratory rate were strong predictors of patient outcome  
- Most critical drop in patient condition occurs during early admission phase  
- Gradient Boosting performed best for multiclass classification  
- Class imbalance impacted baseline models but improved after tuning  
- Early prediction can significantly support ICU prioritization  

---

## 📈 Results & Discussion

- Machine learning models successfully predicted patient disposition outcomes  
- Ensemble methods performed better than linear models  
- Feature engineering significantly improved model accuracy  
- The system can assist clinicians in early decision-making and risk stratification  

---

## 📌 Conclusion

This project demonstrates the successful application of machine learning in healthcare analytics. The predictive model developed can assist hospitals in:

- Early identification of high-risk patients  
- Improving patient management efficiency  
- Optimizing resource allocation (beds, ICU, staff)  
- Supporting data-driven clinical decisions  

Overall, the study highlights how AI can transform traditional healthcare systems into **predictive and intelligent decision-support systems**.

---

## 📂 Project Contents

- Dataset (Excel format)  
- Python Code (Jupyter Notebook)  
- Model Outputs  
- Visualizations & Charts  
- Documentation Report  
