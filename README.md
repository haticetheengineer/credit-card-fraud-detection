# 💳 Credit Card Fraud Detection using Machine Learning

A machine learning project that compares multiple classification algorithms for detecting fraudulent credit card transactions. The objective is to identify suspicious transactions with high accuracy while addressing the challenges of an imbalanced dataset.

---

## 📌 Project Overview

Credit card fraud has become one of the major financial security challenges worldwide. This project evaluates the performance of several supervised machine learning algorithms on a real-world anonymized credit card transaction dataset containing over **550,000 transactions**.

The study focuses on comparing different models using commonly accepted evaluation metrics to determine the most suitable algorithm for fraud detection.

---

## 📂 Dataset

* **Dataset:** Credit Card Fraud Detection Dataset (2023)
* **Transactions:** 550,000+
* **Target Classes:**

  * 0 → Legitimate Transaction
  * 1 → Fraudulent Transaction

> Due to licensing restrictions, the dataset is **not included** in this repository. Please download it from its original source.

---

## 🛠️ Data Preprocessing

The following preprocessing steps were applied before model training:

* Missing value inspection
* Exploratory Data Analysis (EDA)
* Class distribution analysis
* Feature scaling using **StandardScaler**
* Train/Test split (80% / 20%)

---

## 🤖 Machine Learning Models

The following classifiers were trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes

---

## 📊 Evaluation Metrics

The models were compared using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🏆 Results

Among all evaluated algorithms, **Random Forest** achieved the best overall performance with the highest F1-score, making it the most effective model for detecting fraudulent transactions.

Decision Tree and Support Vector Machine also demonstrated competitive performance, while Naive Bayes produced comparatively lower results.

---

## 📁 Repository Structure

```text
credit-card-fraud-detection-ml/
│
├── credit-fraud-detection-ml.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection-ml.git
```

Install the required packages

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📈 Future Improvements

* Hyperparameter Optimization (Grid Search / Random Search)
* SMOTE for handling class imbalance
* ROC and Precision-Recall Curves
* Feature Importance Visualization
* SHAP Explainability
* XGBoost and LightGBM comparison
* Streamlit deployment for real-time prediction

---

## 👩‍💻 Author

**Hatice Tekiş**

Research interests include Artificial Intelligence, Machine Learning, Computer Vision, Medical Image Analysis, and Embedded Systems.

---

## 📄 License

This project is released under the **MIT License**.
