# Logistic Regression from Scratch

This project builds a **logistic regression classifier** from scratch using only **NumPy**, without any ML libraries. 
It explores the algorithm across different types of data: linearly separable, non-linearly separable (circular), and real-world medical data.

---

## What’s Inside

- Implementation of:
  - Sigmoid activation
  - Binary cross-entropy loss
  - Gradient descent optimization
- Experiments on:
  - **Linearly separable data**
  - **Circular (non-linear) data**
  - **Real-world Pima Diabetes dataset**
- Comparison with **Scikit-learn's** LogisticRegression

---

## Datasets Used

- **Synthetic Linear Data** – cleanly separable, tests baseline performance  
- **Circular Data** – non-linearly separable to test model limitations  
- **Pima Indians Diabetes Dataset** – real-world data to evaluate generalization

---

## Learning's

- How logistic regression separates data using decision boundaries  
- Where and why it fails when data isn't linearly separable  
- Feature normalization and handling missing values in real-world data  
- Comparing from-scratch implementation to library results

---

## Tools Used

- Python, NumPy, Matplotlib  
- Scikit-learn (only for data loading & validation)

---

## Files

- `logistic_regression_linear.ipynb` – Custom model on linear synthetic data  
- `logistic_regression_nonlinear.ipynb` – Custom model fails on circular data so we use polynomial features 
- `logistic_regression_real_dataset.ipynb` – From-scratch logistic regression on Pima diabetes dataset

---