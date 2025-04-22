# 🧠 Multi-Domain Data Mining Project

This repository contains three end-to-end machine learning tasks across diverse domains — real estate price prediction, e-commerce shopper behavior classification, and sentiment analysis of Amazon product reviews. The goal is to demonstrate the application of regression, classification, and NLP techniques using real-world datasets.

---

## 📊 Project Overview

### 1. Real Estate Price Prediction (Regression)
- Dataset: King County housing data (USA)
- Engineered features like luxury indicators (pools, basements) and spatial features (distance to downtown)
- Best Model: `XGBoost`
- **Performance:** R² = 0.93

### 2. E-commerce Shopper Purchasing Intention (Classification)
- Addressed class imbalance using `SMOTE`, `undersampling`, and `SMOTE + ENN`
- Best Model: `Gradient Boosting + SMOTEENN`
- **Accuracy:** 88%

### 3. Sentiment Analysis of Amazon Product Reviews (Text Classification)
- Text preprocessing: Lemmatization, stop word removal, TF-IDF vectorization
- Balanced dataset using `SMOTE`
- Best Model: `Logistic Regression` with hyperparameter tuning
- **Accuracy:** 85%
- Word cloud analysis revealed drivers of satisfaction and frustration

---

## 🧰 Technologies & Libraries

- Python
- Jupyter Notebook
- pandas, NumPy
- scikit-learn
- XGBoost
- imbalanced-learn (SMOTE, ENN)
- Matplotlib, Seaborn
- NLTK / spaCy (for text processing)

---


