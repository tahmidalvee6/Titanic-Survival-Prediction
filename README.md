# 🚢 Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

> Predicting whether a passenger survived the Titanic disaster using Machine Learning.

---

## 📌 Project Overview

This is a beginner level end to end Machine Learning classification project. Based on passenger information like age, sex, and ticket class, we predict whether a passenger survived or not.

- **Dataset:** Titanic - Machine Learning from Disaster (Kaggle)
- **Total Passengers:** 891
- **Target:** Survived (0 = No, 1 = Yes)
- **Task Type:** Binary Classification

---

## 📁 Folder Structure

```
Titanic-Survival-Prediction/
│
├── train.csv
└── titanic.ipynb
```

---

## 🔧 Libraries Used

| Library | Purpose |
|--------|---------|
| Pandas | Data loading and manipulation |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Scikit-Learn | Machine learning models |

---

## 📊 Project Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | Environment Setup | Import all libraries |
| 02 | Data Loading | Load CSV and check structure |
| 03 | Data Inspection | Check nulls, dtypes, statistics |
| 04 | Data Cleaning | Handle missing values, encode text |
| 05 | EDA & Visualization | Explore patterns with charts |
| 06 | Train Test Split | 80% train / 20% test |
| 07 | Model Training | Train 3 ML models |
| 08 | Prediction | Predict on test data |
| 09 | Evaluation | Compare model accuracies |

---

## 🤖 Models Used

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 79.89% |
| Random Forest | **82.68%** ✅ |
| SVM | 65.36% |

> ✅ **Random Forest** gave the best accuracy of **82.68%**

---

## 📈 Features Used

| Feature | Description |
|---------|-------------|
| Pclass | Passenger ticket class (1, 2, 3) |
| Sex | Gender (0 = Male, 1 = Female) |
| Age | Age of passenger |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Fare | Ticket fare |
| Embarked | Port of embarkation (S, C, Q) |

---


## 📬 Contact

[![GitHub](https://img.shields.io/badge/GitHub-tahmidalvee6-black.svg?logo=github)](https://github.com/tahmidalvee6)
