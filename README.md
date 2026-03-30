# 🚨 Fake Job Posting Detection (ML + NLP)

## 📌 Overview

This project focuses on detecting **fraudulent job postings** using Machine Learning and Natural Language Processing (NLP).

The system analyzes both **textual data** (job descriptions, requirements, company profiles) and **structured features** (company logo, telecommuting, etc.) to classify whether a job post is **legitimate or fake**.

---

## 🎯 Problem Statement

Online job portals often contain **fraudulent job listings** that can mislead applicants.
This project aims to build an intelligent system that can **automatically detect fake job postings** and reduce such risks.

---

## ⚙️ Features

* 📄 Text preprocessing (cleaning, stopword removal, lemmatization)
* 🔤 TF-IDF vectorization for text representation
* 📊 Feature engineering (text length, salary presence, etc.)
* ⚖️ Handling imbalanced data using SMOTE
* 🤖 Multiple ML models:

  * Logistic Regression
  * Naive Bayes
  * Support Vector Machine (SVM)
  * Random Forest
* 🔍 Hyperparameter tuning using Optuna
* 📉 Threshold optimization for better fraud detection
* 📊 Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
  * ROC-AUC
* 🧠 Production-ready prediction system

---

## 📂 Dataset

* Source: Kaggle Fake Job Postings Dataset
* Contains:

  * Job title, description, requirements
  * Company details
  * Binary target: `fraudulent`

---

## 🧪 Model Pipeline

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. TF-IDF Vectorization
4. Train-Test Split
5. Handling Imbalance (SMOTE)
6. Model Training
7. Hyperparameter Tuning
8. Evaluation & Comparison
9. Threshold Optimization
10. Final Prediction System

---

## 📊 Results

* Best Model: Logistic Regression (Tuned)
* Achieved high performance using:

  * F1-score (important for imbalance)
  * ROC-AUC
* Improved fraud detection using optimized threshold instead of default 0.5

---

## 🚀 How to Run

### ▶️ Option 1: Open in Google Colab (Recommended)

https://colab.research.google.com/drive/1wT-_7b4QgLOIRxiDLUxHU-2x0d5qDA0S#scrollTo=y4KftHFEBPdj


## 🧠 Key Learnings

* Importance of handling **imbalanced datasets**
* Role of **feature engineering in NLP tasks**
* Why **F1-score is better than accuracy** in fraud detection
* Practical use of **TF-IDF + ML models**
* Model optimization using **Optuna**

---

## ⚠️ Limitations

* Model depends on dataset quality
* May struggle with very short or ambiguous job descriptions
* Real-world fraud patterns may evolve over time

---

## 🔮 Future Improvements

* Add deep learning (BERT-based models)
* Deploy using Streamlit / Web App
* Real-time job scraping and detection
* Explainable AI (SHAP, LIME)

---

## 💼 Resume Highlight

**Fake Job Posting Detection System (ML + NLP)**
Developed a machine learning system to classify fraudulent job postings using TF-IDF and multiple classification models. Improved performance using SMOTE and hyperparameter tuning, achieving strong F1-score and ROC-AUC.

---

## 👨‍💻 Author

**Shirish B**
Computer Science Student | AI/ML Enthusiast

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
