# 🩺 Diabetes Risk Classification Using Machine Learning

A Health Data Science portfolio project focused on diabetes risk prediction using machine learning and clinically relevant model evaluation.


---

## ♾️ Project Overview

This project explores the use of machine learning for *diabetes risk classification* using clinical and demographic health data.

The goal was not only to build predictive models, but also to follow a structured *Health Data Science workflow* including:

- Data quality assessment
- Exploratory Data Analysis
- Preprocessing
- Machine learning model development
- Performance evaluation
- Clinical interpretation

---

## 🎯 Objectives

- Understand the structure of the dataset
- Identify clinically implausible values
- Perform exploratory data analysis
- Apply appropriate preprocessing
- Train multiple classification models
- Compare model performance
- Interpret false negatives from a healthcare perspective

---

## 📊 Dataset

The dataset includes the following variables:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome

### Target Variable

- 0 = Non-diabetic
- 1 = Diabetic

---

## 🧹 Data Preparation

The dataset was checked for:

- Missing values
- Invalid or clinically implausible zero values
- Outliers
- Class imbalance
- Feature distributions

Special attention was given to variables where a zero value may represent missing information rather than a true clinical measurement.

---

## 🔍 Exploratory Data Analysis

EDA was performed to investigate:

- Class distribution
- Feature distributions
- Potential outliers
- Correlations between variables
- Differences between diabetic and non-diabetic groups

---

## 🤖 Machine Learning Models

Three classification models were evaluated:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.701 | 0.591 | 0.481 | 0.531 | 0.818 |
| Random Forest | 0.747 | 0.660 | 0.574 | 0.614 | 0.814 |
| SVM | 0.734 | 0.600 | 0.722 | 0.655 | 0.810 |

---

## 🏆 Key Findings

- *Logistic Regression* achieved the highest ROC-AUC.
- *Random Forest* achieved the highest accuracy and precision.
- *SVM* achieved the highest recall and F1-score.

These results show that different models provide different trade-offs depending on the evaluation metric.

---

## ❤️ Health Data Science Perspective

In healthcare prediction tasks, accuracy alone may not be enough.

For diabetes risk classification, *recall or sensitivity is especially important* because a false negative represents a person with diabetes who is incorrectly classified as non-diabetic.

From this perspective, the SVM model performed well because it achieved the highest recall among the tested models.

However, this project is intended for educational and portfolio purposes and should not be considered a clinically validated diagnostic tool.

---

## 🧠 Key Learning Outcomes

Through this project, I gained practical experience in:

- Healthcare data cleaning
- Exploratory Data Analysis
- Identifying hidden missing values
- Data preprocessing
- Leakage-free modelling workflow
- Binary classification
- Logistic Regression
- Random Forest
- Support Vector Machine
- Confusion matrix analysis
- Precision, Recall and F1-score
- ROC-AUC evaluation
- Clinical interpretation of model errors

---

## ⚠️ Limitations

- The dataset is relatively small
- Some variables contain implausible zero values
- The dataset represents a specific population
- External validation was not performed
- The models were not tested in a real clinical setting

Therefore, the results should not be directly generalised to real-world healthcare practice.

---

## 🛠️ Tools & Technologies

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🤖 Scikit-learn
- ☁️ Google Colab
- 🐙 GitHub

---

## 📓 Project Notebook

The complete analysis, code, visualisations and model evaluation are available in:

diabetes_risk_classification.ipynb

---

## 🚀 Portfolio Context

This project was developed as part of my preparation for postgraduate study in *Health Data Science*.

It reflects my interest in applying data analysis and machine learning methods to healthcare-related problems while considering both technical performance and clinical relevance.

---

## ⚕️ Disclaimer

This project is for educational and portfolio purposes only.

It is not intended for medical diagnosis, treatment decisions or real-world clinical deployment.
Sent 3m ago
