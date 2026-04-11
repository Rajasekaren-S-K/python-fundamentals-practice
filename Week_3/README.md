<div align="center">

# 📈 Week 3 — Machine Learning: Regression
### Hope AI Master Program · Applied AI, Gen AI & Data Science

![Status](https://img.shields.io/badge/Status-✅%20Completed-brightgreen?style=for-the-badge)
![Module](https://img.shields.io/badge/Module-Regression%20Analysis-4B8BBE?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC4E20?style=for-the-badge)

> **Can machine learning predict what you'll pay for health insurance?**
> This week's assignment answers exactly that — by building, training, and benchmarking 6 regression models on real-world insurance data.

</div>

---

## 🎯 Problem Statement

Medical insurance costs vary wildly based on age, lifestyle, and health factors. The goal of this assignment is to **build a predictive regression model** that accurately estimates insurance charges for a given individual — a real-world problem that sits at the intersection of healthcare, actuarial science, and machine learning.

---

## 📂 Assignment

| Item | Detail |
|------|--------|
| 📓 Notebook | `Assignment-Regression.ipynb` |
| 📊 Dataset | `insurance_pre.csv` |
| 🎯 Target Variable | `charges` (medical insurance cost in USD) |
| 🔢 Features Used | `age`, `sex`, `bmi`, `children`, `smoker` |
| ✂️ Train / Test Split | 70% / 30% |
| 📐 Evaluation Metric | R² Score (Coefficient of Determination) |

---

## 🔬 ML Pipeline

```
Raw Data
   │
   ├── 1. Exploratory Data Analysis (EDA)
   │       └── Shape, dtypes, null check, statistical summary
   │
   ├── 2. Outlier Detection & Removal
   │       └── IQR method on BMI & Charges columns
   │
   ├── 3. Feature Engineering
   │       └── Label encoding: sex (0/1), smoker (0/1)
   │
   ├── 4. Feature Scaling
   │       └── StandardScaler (for boosting models)
   │
   ├── 5. Train / Test Split
   │       └── 70% train · 30% test · random_state=0
   │
   └── 6. Model Training & Evaluation
           └── 6 models trained → R² Score compared → Best model selected
```

---

## 🤖 Models Benchmarked

| # | Model | Category | Key Strength |
|---|-------|----------|-------------|
| 1 | **Linear Regression** | Baseline | Fast, interpretable, assumes linearity |
| 2 | **Decision Tree Regressor** | Tree-based | Captures non-linear patterns |
| 3 | **Random Forest Regressor** | Ensemble (Bagging) | Reduces variance, robust to noise |
| 4 | **Gradient Boosting Regressor** | Ensemble (Boosting) | Sequentially corrects errors |
| 5 | **AdaBoost Regressor** | Ensemble (Boosting) | Adaptive weighting of weak learners |
| 6 | **XGBoost Regressor** | Ensemble (Boosting) | Regularized, high-performance GBDT |

---

## 🛠️ Tech Stack

```python
libraries = {
    "Data Wrangling" : ["pandas", "numpy"],
    "Visualization"  : ["matplotlib", "seaborn"],
    "ML Models"      : ["scikit-learn", "xgboost"],
    "Preprocessing"  : ["StandardScaler", "LabelEncoder", "train_test_split"],
    "Evaluation"     : ["r2_score"],
}
```

---

## 📁 Folder Structure

```
Week_3/
├── Assignment-Regression.ipynb   # Full ML pipeline & model comparison
└── README.md                     # This file
```

---

## 💡 Key Learnings

- Real-world data is messy — outlier removal with IQR made a measurable difference in model performance
- Ensemble methods consistently outperform single-model approaches on tabular data
- Boosting algorithms (especially XGBoost) capture complex feature interactions that linear models miss
- StandardScaler is critical for boosting models; tree-based models are scale-invariant

---

<div align="center">

**← [Back to Main Repo](../README.md)**

*Week 3 of the Hope AI Master Program — Applied AI, Gen AI & Data Science 🚀*

</div>
