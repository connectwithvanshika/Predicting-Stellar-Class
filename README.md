# Predicting Stellar Class using Machine Learning

## Overview

This project focuses on predicting the class of celestial objects using astronomical observation data. The model classifies objects into one of the following categories:

* 🌟 STAR
* 🌌 GALAXY
* ✨ QSO (Quasi-Stellar Object / Quasar)

Using photometric measurements, redshift values, and spectral information, the goal is to build a machine learning model capable of accurately identifying the type of astronomical object.

---

## Dataset

The dataset contains observations collected from astronomical surveys and includes:

| Feature           | Description                         |
| ----------------- | ----------------------------------- |
| alpha             | Right Ascension coordinate          |
| delta             | Declination coordinate              |
| u, g, r, i, z     | Photometric filter magnitudes       |
| redshift          | Redshift measurement                |
| spectral_type     | Stellar spectral classification     |
| galaxy_population | Galaxy population category          |
| class             | Target variable (STAR, GALAXY, QSO) |

### Dataset Size

* Training Samples: **577,347**
* Test Samples: **247,435**
* Features: **11**

---

## Problem Statement

Given astronomical observations, predict the correct celestial object category.

This is a **multi-class classification problem** where the target classes are:

* STAR
* GALAXY
* QSO

---

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost / LightGBM (if used)
* Matplotlib
* Seaborn
* Kaggle Notebook Environment

---

## Project Workflow

### 1. Data Exploration

* Dataset inspection
* Missing value analysis
* Feature distribution analysis
* Target class distribution

### 2. Data Preprocessing

* Encoding categorical features
* Feature selection
* Data cleaning
* Train-validation split

### 3. Model Building

* Machine Learning Classification Models
* Hyperparameter tuning
* Cross-validation

### 4. Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report
* Validation Performance Analysis

### 5. Prediction

* Generate predictions on unseen test data
* Create Kaggle submission file

---

## Results

The model successfully learns astronomical patterns from photometric and spectral features to classify celestial objects with high accuracy.

Key predictive signals include:

* Redshift
* Spectral Type
* Photometric Magnitudes (u, g, r, i, z)
* Galaxy Population

---

## Repository Structure

```bash
├── train.csv
├── test.csv
├── submission.csv
├── stellar_class_prediction.ipynb
├── README.md
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/connectwithvanshika/Predicting-Stellar-Class.git
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Run Notebook

Open the notebook and execute all cells:

```bash
jupyter notebook
```

---

## Real-World Applications

* Astronomical object classification
* Sky survey analysis
* Space research
* Automated observatory pipelines
* Astrophysics data analysis

---

## Author

**Vanshika Yadav**

* Kaggle Enthusiast
* Machine Learning Learner
* Web Developer
* Open Source Contributor

GitHub: https://github.com/connectwithvanshika

---

### If you found this project useful, consider giving the repository a star!
