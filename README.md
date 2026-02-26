# MNIST-Digit-Classifier-8-8
This project implements a Machine Learning classifier to recognize handwritten digits (0–9) from 8×8 grayscale images using Logistic Regression.

The dataset is sourced from sklearn.datasets.load_digits, which contains smaller 8×8 pixel images (not the 28×28 deep learning MNIST version).

---
## Dataset Details

Total Samples: 1,797
Image Size: 8 × 8 pixels
Features: 64 numerical pixel intensity values
Classes: 10 (Digits 0–9)
Pixel values range from 0–16
Each image is flattened into a 64-dimensional feature vector before training.

---

## Workflow

1️. Data Loading using Scikit-learn
2️. Exploratory Data Analysis (EDA)
3️. Train-Test Split (80–20)
4️. Feature Scaling using StandardScaler
5️. Model Training using Logistic Regression
6️. Model Evaluation

---
## Model Used
- Logistic Regression

- Multi-class classification (One-vs-Rest)

- max_iter=1000

- Scaled input features

- Achieved ~97.2% accuracy on test data
---

## Model Performance

Accuracy: ~97.2%

High precision and recall across all digit classes

Confusion matrix visualization included

---

##  Tech Stack

- Python (Jupyter)
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
---



🎯 Objective

To build a reliable multi-class classifier for handwritten digit recognition using classical machine learning techniques and evaluate its performance.
