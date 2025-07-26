# Bank Marketing Decision Tree Classifier

This project demonstrates how to build, evaluate, and visualize a **Decision Tree Classifier** using the [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) from the UCI Machine Learning Repository.

It was developed in **Google Colab** and focuses on predicting whether a client will subscribe to a term deposit (`y`) based on various client and campaign features.

---

## Dataset Overview

The dataset `bank-full.csv` contains information about:

- Client attributes: age, job, marital status, education, default, balance, etc.
- Campaign-related info: contact type, month, number of contacts, outcome of previous campaign
- Output variable: `y` (has the client subscribed to a term deposit? Yes/No)

---

## Objectives

- Load and preprocess the dataset
- Encode categorical variables using LabelEncoder
- Split the dataset into training and testing sets
- Train a **Decision Tree Classifier** using `scikit-learn`
- Evaluate the model using:
  - Confusion Matrix
  - Accuracy Score
- Visualize the trained Decision Tree

---

## Tools Used

- Python 3.10+
- Google Colab
- Pandas, NumPy
- scikit-learn
- Matplotlib

---

## Model Performance

- Accuracy: ✅ Displayed using `accuracy_score`
- Confusion Matrix: ✅ Built using `pd.crosstab()` or `confusion_matrix()`
- Tree Visualization: ✅ Rendered using `plot_tree()` from `sklearn.tree`

---

## Decision Tree Visualization

The final decision tree is visualized using `matplotlib`, showing how the model makes decisions based on features like:

- Contact month
- Marital status
- Duration of previous calls
- Number of contacts during campaign

---
