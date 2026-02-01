
# Titanic Survival Prediction

### Supervised Machine Learning

## Overview

This project applies a supervised machine learning workflow to predict passenger survival on the Titanic using structured tabular data.
The focus is on practicing the complete ML process, from data exploration and preprocessing to model training and evaluation.

---

## Dataset

* **Titanic: Machine Learning from Disaster**
* **Target variable:**

  * `Survived`

    * `0` → did not survive
    * `1` → survived

---

## Workflow

* Loaded and explored the dataset to understand structure, distributions, and missing values
* Performed exploratory data analysis to identify important features
* Cleaned and prepared the data by handling missing values and encoding categorical variables
* Trained a baseline **Logistic Regression** model
* Trained a **Random Forest** model for comparison and feature importance analysis
* Evaluated models using accuracy, classification metrics, and cross-validation

---

## Results

Both Logistic Regression and Random Forest achieved similar performance (~82% accuracy).
Given the marginal difference, the simpler model remains competitive, while the Random Forest model provides useful insights through feature importance.

---

## Files

* `titanic_supervised_ml.ipynb` — complete EDA and modeling workflow
* `train.csv` — dataset
