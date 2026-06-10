# Credit Card Fraud Detection using Machine Learning

## Project Overview
This repository contains a machine learning project developed for **CS4824 (Machine Learning)** at **Virginia Tech**. The primary objective is to build and optimize predictive models capable of identifying fraudulent credit card transactions within a highly imbalanced dataset.

## Key Objectives & Challenges
* **Imbalanced Dataset:** Fraudulent transactions account for a very small fraction of the overall dataset, making traditional accuracy metrics misleading.
* **Optimization Metric:** The project focuses on optimizing **Precision-Recall (PR)** and the Area Under the Precision-Recall Curve (AUPRC) to effectively minimize false negatives (missed frauds) while maintaining a reasonable false positive rate.
* **Core Model:** Extensive application of **Logistic Regression**, combined with threshold tuning and advanced data handling techniques, to maximize fraud detection performance.

## Repository Structure
* `CS4824_Final_Project (1).ipynb` : The main Jupyter Notebook containing Exploratory Data Analysis (EDA), data preprocessing, model training, and performance evaluation.
* `Final Report.pdf` : A comprehensive document detailing the project's methodology, mathematical background, experimental results, and conclusions.
* `project proposal.pdf` : The initial project scope, dataset description, and planned approach.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## Methodology
1. **Data Preprocessing:** Scaling features (such as Time and Amount) and addressing data anomalies.
2. **Handling Imbalance:** Applying techniques to balance the class distribution and adjusting classification decision thresholds.
3. **Model Training:** Training Logistic Regression to accurately classify transactions as legitimate or fraudulent.
4. **Evaluation:** Utilizing Confusion Matrix, Precision, Recall, F1-Score, and PR-AUC to better reflect the model's performance on the critical minority class.

## 👨‍💻 Author
* Krishna Mattaparthi, Justin Jiang, Hemansh Adunoor, Kyoungnam Moon
