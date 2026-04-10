# Linear Models from Scratch for Apartment Price Prediction

This project explores apartment price prediction using linear models implemented both **from scratch** and with **scikit-learn**.  
The main focus is on understanding how linear regression and regularization work in practice, as well as comparing custom implementations with library-based solutions.
## Project Goal
The goal of this project is to:
- implement core linear models from scratch,
- study the effect of regularization,
- compare custom implementations with `scikit-learn`,
- analyze the impact of feature scaling and target transformation,
- observe underfitting / overfitting behavior in practice.

## Dataset

The project uses a real estate dataset for **apartment price prediction**.

Target:
- apartment price

Features include:
- numerical characteristics such as number of rooms / bathrooms / bedrooms,
- additional apartment or housing attributes,
- engineered binary features based on available amenities.

## Implemented in This Project

### From scratch
- Linear Regression
- Analytical solution for Linear Regression
- Ridge Regression (L2)
- Lasso Regression (L1)
- Elastic Net
- Feature scaling utilities

## Key Results

Main takeaways from the project:
- custom linear models produced results close to `scikit-learn`,
- feature scaling improved training stability and model quality,
- regularization helped control model complexity,
- log transformation of the target improved prediction quality,
- high-degree polynomial features led to strong overfitting.

## Tech Stack

- Python
- NumPy
- Pandas
- scikit-learn
- Jupyter Notebook
## Repository Structure
```text
linear-models-from-scratch/
├── README.md
├── linear_regression_project.ipynb
├── requirements.txt
└── images/