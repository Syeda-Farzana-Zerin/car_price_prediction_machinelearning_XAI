# Car Price Prediction using Machine Learning and LIME Explainability

This project explores car price prediction using a real-world dataset from CarDekho.
It includes complete EDA, six shallow machine-learning models, and LIME explanations for model interpretability.

The accompanying Jupyter Notebook (car_price_lime.ipynb) contains all steps from data loading to explainable predictions.

# Project Features

Exploratory Data Analysis (EDA)

Data summary, distributions, correlations, outlier detection

# Dataset
https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho/data?select=CAR+DETAILS+FROM+CAR+DEKHO.csv
Downloaded and renamed as vehicles.csv

# Preprocessing

Label encoding of categorical features

Train/test split

# Six ML Models

Linear Regression

Decision Tree

Random Forest

Gradient Boosting

KNN Regressor

Support Vector Regression (SVR)

# Model Evaluation

R² Score

RMSE

# Explainable AI

LIME Tabular explanations to interpret individual predictions

#📁 Repository Structure
├── CAR DETAILS FROM CAR DEKHO.csv
├── car_price_lime.ipynb
├── README.md

# Installation
Clone the repository
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo

Install dependencies
pip install -r requirements.txt



# How to Run
jupyter notebook car_price_lime.ipynb


# Results

Random Forest typically performs the best

LIME allows detailed per-instance interpretation, showing which car features increased or decreased the predicted price

# Explainability with LIME
The notebook generates:
Feature contribution tables
Visual interpretation plots
Explaining why the model predicted a certain price for any selected car.
