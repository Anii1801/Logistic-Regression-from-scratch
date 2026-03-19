# ❤️ Heart Disease Prediction using Logistic Regression

## 📌 Overview

This project implements a **Logistic Regression model** to predict the presence of heart disease based on patient health data.

The goal is to understand how machine learning models can be applied to real-world healthcare datasets for binary classification problems.

---

## 🎯 Objective

To build a classification model that can predict whether a person is likely to have heart disease based on various medical attributes.

---

## 📊 Dataset

* Dataset used: Heart Disease Dataset (`1-heart.csv`)
* Target variable: `target` (0 = No Disease, 1 = Disease)

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn

---

## 🔍 Steps Performed

### 1. Data Loading

* Loaded dataset using Pandas
* Previewed data using `.head()`

### 2. Data Cleaning

* Checked for missing values
* Checked for duplicate entries

### 3. Feature Selection

* Split dataset into:

  * Features (X)
  * Target (y)

### 4. Train-Test Split

* Used `train_test_split`
* 80% training, 20% testing

### 5. Model Training

* Used `LogisticRegression`
* Increased `max_iter` to ensure convergence

### 6. Prediction

* Generated predictions on test data

### 7. Evaluation

* Accuracy Score
* Precision Score

---

## 📈 Results

* Model achieved **good accuracy** on test data
* Successfully classified patients based on health features

---

## 🧠 Key Learnings

* Understanding of classification problems
* Importance of data preprocessing
* How Logistic Regression works in real scenarios
* Model evaluation using metrics like accuracy and precision

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install pandas numpy scikit-learn seaborn
```

2. Run the notebook:

```bash
jupyter notebook
```

3. Open and execute:

```
heart_disease.ipynb
```

---

## 📌 Future Improvements

* Add data visualization (correlation heatmap, feature importance)
* Use more evaluation metrics (Recall, F1-score, Confusion Matrix)
* Try other models (Decision Tree, Random Forest)
* Deploy using Streamlit

---

## 👨‍💻 Autho

**Aniruddha Singh**

* GitHub: https://github.com/Anii1801/Logistic-Regression-from-scratch/
* LinkedIn: https://www.linkedin.com/posts/aniruddha-singh-334a8a34b_machinelearning-logisticregression-linearregression-activity-7439398448602259457-BHpX?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFeL9VgBh6FmYDCek34gL8Nb5PhT_NKLDSs
