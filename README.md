# 🌲 Heart Disease Prediction – Decision Tree & Random Forest

This project was completed for **Day 5 of the AI/ML Internship**, where the goal was to build and compare tree-based classification models using the **Heart Disease Dataset**.

---

## 📌 Objectives

- ✅ Train a **Decision Tree Classifier**
- ✅ Visualize the full decision tree
- ✅ Prevent overfitting using `max_depth`
- ✅ Train a **Random Forest Classifier**
- ✅ Interpret **feature importances**
- ✅ Evaluate with **cross-validation**

---

## 📂 Dataset

- 📥 Source: [Kaggle – Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- 🎯 Target Column: `target`
  - `0` → No heart disease
  - `1` → Has heart disease

---

## 🌳 Decision Tree Results

| Version     | Accuracy |
|-------------|----------|
| Full Tree   | 98.54%   |
| Pruned Tree (max_depth=4) | 80.00% |

- 📉 Full tree showed signs of overfitting.
- ✂️ Pruning reduced overfitting at the cost of accuracy.

---

## 🌲 Random Forest Results

- ✅ Accuracy: **98.54%**
- 🔁 5-Fold Cross-Validation Accuracy: **99.71%**
- 🔍 Feature Importance showed `thal`, `cp`, `ca` as most influential

---

## 📊 Feature Importance (Random Forest)

Bar chart was generated using `rf.feature_importances_`  
Top features: `thal`, `ca`, `cp`, `oldpeak`, `age`

---

## 🛠 Libraries Used

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`

---

## 📁 Files Included

- `Day5_DecisionTree_RandomForest_HeartDisease.ipynb`
- `heart.csv`
- `README.md`
- `screenshots/`


---

## ✅ Internship Submission

> This project was completed as part of **Day 5 – AI & ML Internship Program**
