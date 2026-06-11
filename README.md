# Comment Category Prediction

## Overview

This project focuses on automatically classifying comments into predefined categories using Natural Language Processing (NLP) and Machine Learning techniques. The solution combines textual information with numerical engagement features such as upvotes and downvotes to improve prediction performance.

The project was developed as part of a Kaggle competition and includes data exploration, feature engineering, model training, evaluation, and submission generation.

---

## Data Exploration

* Dataset shape analysis
* Missing value detection
* Target label distribution analysis
* Class imbalance inspection
* Statistical summaries

---

## Data Visualization

* Target label distribution
* Upvote distribution
* Downvote distribution
* Exploratory plots for understanding feature behavior

---

## Feature Engineering

### Text Features

* TF-IDF Vectorization
* Unigrams and Bigrams
* Stop-word Removal
* Maximum Feature Selection

### Numerical Features

* Upvotes
* Downvotes
* Standard Scaling

---

## Model Building

### Logistic Regression

* Class-weight balancing
* TF-IDF + Numerical Feature Pipeline
* Hyperparameter tuning using RandomizedSearchCV

### Linear Support Vector Machine (Linear SVC)

* TF-IDF text representation
* Standardized numerical features
* Class imbalance handling

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* Macro F1-Score
* Confusion Matrix
* Classification Report

---

## Hyperparameter Optimization

Randomized Search Cross Validation was used to optimize:

* Regularization Strength (C)
* Model performance on imbalanced classes
* Weighted F1 Score

---

## Project Workflow

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. TF-IDF Feature Extraction
4. Numerical Feature Scaling
5. Model Training
6. Hyperparameter Tuning
7. Performance Evaluation
8. Competition Submission Generation

---

## Skills Demonstrated

* Natural Language Processing (NLP)
* Text Classification
* Feature Engineering
* Machine Learning Pipelines
* Hyperparameter Tuning
* Model Evaluation
* Data Visualization
* Scikit-Learn


