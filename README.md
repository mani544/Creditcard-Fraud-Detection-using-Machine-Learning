
---

# **Credit Card Fraud Detection 🔍💳**

![Image](https://github.com/mani544/Creditcard-Fraud-Detection-using-Machine-Learning/blob/main/ML%20CREDIT.jpg)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Modeling%20%26%20ML-F7931E?logo=scikit-learn\&logoColor=white)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=kaggle)

A machine learning project using **Anomaly Detection Techniques** to identify **fraudulent credit card transactions** in a highly imbalanced dataset.

---

## ⭐ **Project Highlights**

* Built using **Isolation Forest**, **Local Outlier Factor (LOF)**, and **One-Class SVM**
* 284,807 transactions processed
* Only **0.172% fraudulent** → real-world class imbalance scenario
* Full EDA, visualizations, anomaly detection, ROC curves & confusion matrices
* Production-ready ML workflow inside Jupyter Notebook

---

## 📂 **Dataset Information**

| Feature                | Description                                         |
| ---------------------- | --------------------------------------------------- |
| **Total Transactions** | 284,807                                             |
| **Fraudulent Cases**   | 492                                                 |
| **Duration**           | 2 days (Sept 2013)                                  |
| **Imbalance Ratio**    | 0.172% fraud                                        |
| **Features**           | Mostly PCA-transformed (V1–V28) for confidentiality |

Dataset Source: *Kaggle Credit Card Fraud Detection Dataset*

---

## 🧪 **ML Models Used**

| Model                          | Type         | Purpose                              |
| ------------------------------ | ------------ | ------------------------------------ |
| **Isolation Forest**           | Unsupervised | Detect anomalies by isolating points |
| **Local Outlier Factor (LOF)** | Unsupervised | Detect local density deviations      |
| **One-Class SVM**              | Unsupervised | Learns boundary around normal data   |

---

## 📈 **Evaluation Metrics**

This project includes:

* Confusion Matrices
* ROC Curves
* AUC-ROC Score
* Accuracy, Precision, Recall
* Fraud/Normal distribution plots

> ⚠ Because of high imbalance, **Precision & Recall** are prioritized over accuracy.

---

## 🛠 **Tech Stack**

* **Python**
* **Pandas, NumPy** – Data Handling
* **Matplotlib, Seaborn** – Visualization
* **Scikit-Learn** – Machine Learning Models
* **Jupyter Notebook**

---

## 🚀 **How to Run This Project**

Clone the repository:

```bash
git clone https://github.com/<your-username>/CreditCard-Fraud-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Notebook:

```bash
jupyter notebook
```

Open:

```
Creditcard_Fraud_Detection.ipynb
```

---

## 📁 **Folder Structure**

```
📦 CreditCard-Fraud-Detection
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┣ 📊 Creditcard_Fraud_Detection.ipynb
 ┣ 📂 data
 ┃ ┗ creditcard.csv
 ┗ 📂 outputs
    ┣ fraud_normal_distribution.png
    ┣ confusion_matrix.png
    ┗ roc_curves.png
```

---

## 🧠 **Key Insights**

* Fraud transactions differ significantly in transaction patterns.
* Isolation Forest & LOF performed best for anomaly detection.
* One-Class SVM was slower and required tuning.
* Imbalanced data requires metrics beyond accuracy.

---

## 🔮 **Future Enhancements**

* Use **Autoencoders** for deep learning anomaly detection
* Deploy as a **Streamlit fraud detection app**
* Create a **real-time monitoring dashboard**
* Try techniques like **SMOTE** or undersampling

---

## 🧑‍💻 **Author**

**Mani Chokkara**
Data Analyst |  AI/ML Enthusiast

---

