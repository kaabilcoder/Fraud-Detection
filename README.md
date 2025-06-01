# 🛡️ Fraud Detection Using Classification Algorithms

This project is a part of my entry-level project, focused on applying classification algorithms to detect fraudulent activities from credit card transactions. The dataset is highly imbalanced, which presents an additional layer of complexity in model building and evaluation.

---

## 📌 Project Overview

The objective of this project is to build a binary classification model that identifies potentially fraudulent transactions in a financial dataset. We explore techniques to handle imbalanced data and use logistic regression for classification.

### 📊 Dataset

- The dataset used is a real-world credit card transactions dataset.
- It contains both legitimate and fraudulent transactions.
- The dataset is highly imbalanced (many more legitimate transactions than fraudulent ones).

---

## ⚙️ Tech Stack

- **Python**
- **Pandas** — for data manipulation
- **NumPy** — for numerical operations
- **Scikit-learn** — for model building and evaluation
- **Google Colab** — for execution environment
---


## 📁 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---
## 🧠 Machine Learning Workflow

1. **Data Preprocessing**
   - Load and explore the dataset
   - Handle missing values
   - Analyze class distribution

2. **Data Balancing**
   - Undersample the majority class to balance with the minority class (fraud cases)

3. **Feature Scaling**
   - Apply `StandardScaler` to normalize transaction values

4. **Model Building**
   - Use **Logistic Regression** as the baseline classification model

5. **Model Evaluation**
   - Accuracy Score
   - Train-test split with stratification
   - Evaluate performance on both classes

---

## 🧪 What I Learned

- Gained a solid understanding of **imbalanced datasets** and why they are challenging in classification problems.
- Learned to use **undersampling techniques** to create a balanced dataset.
- Applied **logistic regression** to real-world data.
- Understood how to evaluate models when class distribution is skewed.
- Built end-to-end fraud detection pipeline from raw data to prediction.

---
## 👨‍💻 Made By
[kaabilcoder](https://github.com/kaabilcoder) ~ Saurabh Kumar Sahu
