---
title: "Financial Fraud in Canada (2021–2025)"
collection: projects
permalink: /project/financial-fraud/
date: 2024-05-01
excerpt: "Analyzed Canadian financial fraud data reported from 2021 to 2025 to identify demographic trends, fraud categories, and key patterns. Applied machine learning models to classify fraud cases and evaluated performance.
<br/><img src='/images/fraud-dashboard.png'>" 
tags: [data-analysis, scikit-learn, classification, eda]
---

![Fraud Classification Dashboard](/images/fraud-dashboard.png)

# Financial Fraud in Canada — Data Analysis & Classification Project

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas)](https://pandas.pydata.org/)
[![Status](https://img.shields.io/badge/Status-Ongoing-yellow)]()

## Overview

This project investigates over 328,000 financial fraud complaints reported in Canada between 2021 and 2025. The goal is to **analyze victim demographics, fraud categories, and reporting patterns**, and build predictive models to help flag potential fraud.

---

## Objectives

- Perform exploratory data analysis (EDA) on fraud complaint data
- Analyze demographic factors like gender and age range
- Identify trends in fraud types and sources by province
- Build classification models to predict fraudulent activity
- Compare model performance using accuracy, precision, recall, and F1-score

---

## Skills & Tools Applied

| Category          | Tools/Skills                                    |
|-------------------|-------------------------------------------------|
| Data Analysis      | Python, Pandas, NumPy                          |
| Data Visualization | Matplotlib, Seaborn                           |
| Machine Learning   | Scikit-learn (Logistic Regression, Decision Tree, Random Forest) |
| Evaluation Metrics | Confusion Matrix, Accuracy, Precision, Recall |
| Project Management | Jupyter Notebook, Git, GitHub                 |

---

## Key Insights

- **Most Common Fraud**: Identity fraud was the most frequently reported category.
- **Top Provinces**: Ontario had the highest number of reported fraud cases.
- **Demographics**: People aged 30–69 were the most frequent fraud victims, especially those 30–39.
- **Gender**: Slightly more female victims were recorded, but the distribution was balanced.
- **Underreporting**: A significant portion of data lacked gender and age details.

---

## Model Comparison

| Model               | Accuracy | Fraud Recall | Fraud Precision | Fraud F1-Score |
|--------------------|----------|--------------|------------------|----------------|
| Logistic Regression| 0.88     | 0.72         | 0.76             | 0.74           |
| Decision Tree       | 0.88     | 0.73         | 0.76             | 0.74           |
| Random Forest       | 0.88     | **0.75**     | 0.76             | **0.75**       |

✅ **Top Performer**: Random Forest Classifier — achieved the best balance between precision and recall.

---

## Conclusion

This analysis of Canadian financial fraud reports highlights the most vulnerable demographics and common fraud types. It also provides a foundation for building ML-based fraud detection tools. The Random Forest model demonstrated the best classification performance, and future work will focus on improving recall, addressing class imbalance, and incorporating additional features like location and timestamps.

---

[🔗 View code on GitHub](https://github.com/helenzhupnyk/Financial_Fraud_Canada)
