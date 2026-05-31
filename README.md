# Predict Podcast Listening Time

A machine learning project focused on predicting podcast listening duration using advanced feature engineering, target encoding, and LightGBM regression.

## Overview

This project aims to estimate how long a user will listen to a podcast episode based on podcast metadata, publication details, popularity metrics, sentiment information, and engineered interaction features.

The solution combines extensive feature engineering with target encoding techniques and gradient boosting models to achieve strong predictive performance.

## Features

* Comprehensive data preprocessing pipeline
* Feature engineering for listener behavior patterns
* Target Encoding with Out-of-Fold (OOF) strategy
* Multi-level encoded feature statistics
* LightGBM regression model
* K-Fold Cross Validation
* Early Stopping for efficient training
* Automated submission generation

## Exploratory Data Analysis

The notebook includes:

* Missing value analysis
* Target distribution visualization
* Feature distribution analysis
* Correlation analysis
* Categorical feature exploration

## Machine Learning Pipeline

### 1. Data Preparation

* Missing value handling
* Categorical feature mapping
* Numerical feature cleaning

### 2. Feature Engineering

* Episode number extraction
* Host and guest interaction features
* Advertisement density features
* Popularity-based interaction metrics
* Rounded grouping features

### 3. Target Encoding

* Single-feature target encoding
* Pairwise target encoding
* Triple-combination target encoding
* Out-of-Fold encoding to prevent data leakage
* Aggregated encoding statistics

### 4. Model Training

* LightGBM Regressor
* K-Fold Cross Validation
* Early Stopping
* RMSE evaluation metric

## Results

The model achieves strong predictive performance through the combination of:

* Advanced feature engineering
* Robust target encoding
* Gradient boosting optimization
* Cross-validation training

## Technologies Used

* Python
* Pandas
* NumPy
* LightGBM
* Scikit-Learn
* Matplotlib
* Seaborn
* TQDM

## Project Structure

```text
predict-podcast-listening-time/
│
├── Predict-Podcast-Listening-Time.ipynb
├── README.md
├── requirements.txt
└── submission.csv
```

## Author
Rayan Alzoubi.
