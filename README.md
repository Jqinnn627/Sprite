# MNIST Digit Classification: KNN vs. Logistic Regression

This repository contains a comparative study of two traditional machine learning algorithms—**K-Nearest Neighbors (KNN)** and **Logistic Regression**—applied to the classic MNIST dataset of handwritten digits.

## ## Project Overview
The goal of this project is to implement and evaluate the performance of a non-parametric model (KNN) against a parametric linear model (Logistic Regression). The project covers data preprocessing, hyperparameter tuning, and performance metrics analysis.

## ## Dataset
The **MNIST** (Modified National Institute of Standards and Technology) dataset consists of:
* **Training Set:** 60,000 images
* **Test Set:** 10,000 images
* **Format:** 28x28 grayscale images (flattened to 784 features)
* **Labels:** Digits 0-9

## ## Methodology

### 1. Data Preprocessing
* **Normalization:** Scaling pixel values from $[0, 255]$ to $[0, 1]$ to ensure faster convergence for Logistic Regression.

### 2. Models
#### **K-Nearest Neighbors (KNN)**
#### **Logistic Regression**

---

## ## Results & Comparison

| Metric | Logistic Regression | K-Nearest Neighbors |
| :--- | :--- | :--- |
| **Accuracy** | ~92% | ~94% |
| **F1_Score** | ~92% | ~94% |
| **ROC-AUC** | ~99% | ~98% |

### Key Findings
* **KNN** generally achieves higher accuracy on MNIST because it captures local structural similarities in the digits.
* **Logistic Regression** is significantly more robust in probabilistic prediction.

## ## Visualization
The project includes scripts to visualize:
* **Confusion Matrices:** To identify which digits are most frequently confused.
* **Missclassified Samples:** Displaying images where the models failed.

---

**Author:** [Ooi Jing Le/Ng Jia Qin]  
**Date:** April 2026
