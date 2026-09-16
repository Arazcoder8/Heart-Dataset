# Machine Learning Project for Heart data

---

## 📌 Overview
Our Goal is To Find Who Has Heart Disease
0 Mean No 1 Mean Yes

---

## 📊 about Dataset 
Number of Columns : 14
Number of Rows : 1025
Number of Duplicates : 723 (We have 302 Rows)
Number of Nan Values : 0
Columns : [age,sex,cp,trestbps,chol,fbs,restecg,thalach,exang,oldpeak,slope,ca,thal,target]
Target : target
Classification Problem

---

### Remove Duplicated Values
The original dataset contains 1025 rows.
After identifying 723 duplicate rows, 302 unique samples remained.
Duplicate rows were removed before model training to reduce repeated observations. 

---

## 🧠 Models
Models Used :

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier
* XGBoost Classifier

---

## ⚙️ Preprocessing

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Scaling
* Missing Value Imputation
* Hyperparameter Tuning
* Model Evaluation
* Evaluation Metrics

---

## 🛠️ Technologies

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Joblib

---

## 📈 Results

Best Model is Random Forest

| Model | Accuracy | Precision | Recall | F1 | ROC-AUC |
|------|----------|-----------|--------|----|---------|
| Random Forest | 85.245902 | 80.555556 | 93.548387| 86.567164 | 91.827957 |

---

## 📂 Project Structure

```text
.
├── data/
├── images/
├── models/
├── Heart.ipynb
├── README.md
└── requirements.txt
```
