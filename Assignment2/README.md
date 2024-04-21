# Medical Appointment No Shows Analysis

This project analyzes a medical appointment dataset from Kaggle to understand factors contributing to patient no-shows.

## Introduction

No-shows can significantly impact healthcare efficiency and patient care. This study aims to identify patterns and develop data-driven strategies for reducing no-show rates.

## Data Analysis

The project utilizes a dataset containing over 110,000 appointments with 14 associated variables related to patients, their health conditions, and communication details. Exploratory Data Analysis (EDA), preprocessing, and modeling techniques are employed:

* **Exploratory Data Analysis (EDA):**
    * Understanding data distribution and relationships between variables to identify potential predictors of no-shows.
    * Visualization techniques like histograms, boxplots etc are used.

* **Preprocessing:**
    * Data cleaning steps like address outliers and etc are applied.
    * Feature engineering.

* **Modeling:**
    * Fine-tuning a Random Forest model and a PyTorch MLP model for classification.

* **Evaluation:**
    * Training and development loss plots over epochs to visualize model learning.
    * A final classification report of the best model, providing metrics like accuracy, precision, recall, and F1-score.
