# 🎓 Student Grade Prediction using Machine Learning

## 📌 Objective
This project predicts student grades (A–F) using demographic features only.

The goal is to build a realistic machine learning model while avoiding data leakage.

---

## 🧠 Problem Type
Multi-Class Classification

---

## ⚙️ Approach

1. Loaded student performance dataset
2. Created `average_score`
3. Assigned strict grades (A–F)
4. Removed exam scores to avoid data leakage
5. Encoded categorical features
6. Applied Decision Tree and Random Forest models
7. Evaluated performance using accuracy
8. Analyzed feature importance

---

## 📊 Results

- Accuracy: ~30%
- Demographic features alone show limited predictive power.
- Lunch type and test preparation had moderate influence.
- No single dominant predictor was found.

---

## 🚫 Data Leakage Prevention

Exam scores were removed before training to ensure realistic model behavior.

---

## 🛠 Tech Stack

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Key Learning

- Feature engineering
- Multi-class classification
- Model comparison
- Feature importance analysis
- Importance of relevant features in ML

---

## 📂 Project Structure

```
student-grade-ml/
│
├── data/
├── notebooks/
├── README.md
└── requirements.txt
```

---

## 🔥 Future Improvements

- Include study hours dataset
- Hyperparameter tuning
- Model deployment using Streamlit
