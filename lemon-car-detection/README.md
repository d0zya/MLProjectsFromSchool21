# Lemon Car Detection with Classification Algorithms from Scratch

This project explores binary classification for detecting risky used cars using models implemented both **from scratch** and with **scikit-learn**.  
The main focus is on understanding how classical classification algorithms work in practice, as well as comparing custom implementations with library-based solutions.

## Project Goal

The goal of this project is to:
- implement core classification algorithms from scratch,
- compare custom implementations with `scikit-learn`,
- study the effect of feature encoding and feature engineering,
- evaluate models using classification metrics relevant to business задачам,
- analyze model quality on temporal train / validation / test splits.

## Dataset

The project uses the **Don’t Get Kicked** dataset for used car risk prediction.

Target:
- whether a car is risky / problematic

Features include:
- vehicle characteristics,
- purchase-related information,
- categorical dealership and auction features,
- encoded and engineered features based on the original dataset.

## Implemented in This Project

### From scratch
- Logistic Regression
- Gaussian Naive Bayes
- K-Nearest Neighbors (KNN)
- Gini metric
- Precision
- Recall
- F1-score
- AUC-PR

### Using libraries
- `LogisticRegression`
- `GaussianNB`
- `KNeighborsClassifier`
- `GridSearchCV`

## Key Results

Main takeaways from the project:
- custom implementations reproduced the logic of classical classification algorithms and produced meaningful results,
- Logistic Regression showed the strongest and most stable performance among the tested models,
- feature engineering slightly improved validation quality,
- KNN performed хуже on this dataset, likely due to feature space structure and encoded categorical variables,
- temporal train / validation / test split made the evaluation setup more realistic,
- hyperparameter tuning improved the final classification quality.

## Tech Stack

- Python
- NumPy
- Pandas
- scikit-learn
- Jupyter Notebook

## Repository Structure

```text
lemon-car-detection/
├── README.md
├── classification_project.ipynb
└── requirements.txt