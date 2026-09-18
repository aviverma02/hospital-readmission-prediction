# Hospital Readmission Prediction

A Machine Learning project for predicting whether a patient is likely to be readmitted to the hospital within 30 days of discharge.

The project uses **Logistic Regression with L2 Regularization** and evaluates the model using **ROC-AUC, Precision, Recall, F1 Score, Accuracy, and Confusion Matrix**.

---

## 📌 Project Overview

Hospital readmissions can increase healthcare costs and put additional pressure on hospital resources.

This project develops a binary classification model that predicts **30-day hospital readmission risk** using patient records, clinical measurements, previous admissions, diagnosis information, and hospital-related features.

The model can help identify patients who may require additional follow-up or care planning.

---

## 🎯 Problem Statement

The objective is to predict:

> **Will a patient be readmitted to the hospital within 30 days?**

The target variable is:

```text
readmitted_30d
