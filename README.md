# 🩺 Diabetes Prediction Using Logistic Regression

This project implements a binary classification model to predict the likelihood of diabetes in patients using logistic regression. The model is developed in two phases: first through a manual implementation using NumPy and then using `scikit-learn` for comparison.

---

## 📊 Dataset Information

The dataset is part of the **Pima Indians Diabetes Database**, originally collected by the **National Institute of Diabetes and Digestive and Kidney Diseases**. All patients in this dataset are **females of Pima Indian heritage** aged **21 years or older**. Several selection constraints were applied to ensure data quality and relevance for medical research.

---

## 🔍 Project Overview

- The model is implemented **manually using NumPy** to understand the fundamentals of logistic regression.
- A second model is built using **`scikit-learn`'s LogisticRegression** for comparison.
- The features are standardized to improve performance and convergence.
- The dataset is split using an 80-20 train-test split to evaluate generalization.
- Accuracy, confusion matrix, and classification report are used for model evaluation.

---

## 🛠️ Tools & Technologies

- Python (NumPy, Pandas)
- Scikit-learn
- Matplotlib


---

## ✅ Results

- **Manual Logistic Regression Accuracy**: ~71.48%
- **Scikit-learn Logistic Regression Accuracy**: ~75.32%

The scikit-learn implementation slightly outperforms the manual version, but both models effectively demonstrate the application of logistic regression for medical predictions.

---

## 💾 Future Work

- Add model regularization
- Try alternative classification algorithms (e.g., SVM, Random Forest)
- Build a user-friendly interface with Flask or Streamlit
- Deploy as a web application

---

## 📁 Dataset Source

Available on [Kaggle: Pima Indians Diabetes Database](https://www.kaggle.com/datasets/kandij/diabetes-dataset)

---

## 🤝 Contact

Feel free to reach out or collaborate if you find this project useful!
