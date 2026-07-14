# Black Friday Sales - Exploratory Data Analysis & Feature Engineering

## Project Overview

This project performs exploratory data analysis (EDA) and feature engineering on the Black Friday Sales dataset.

The objective is to understand customer purchasing behavior, preprocess the dataset, engineer machine learning features, and prepare the data for purchase amount prediction.

---

## Dataset

The dataset contains customer demographic information, product categories, and purchase amounts collected during a Black Friday sales event.

### Features include:

* Gender
* Age
* Occupation
* City Category
* Years in Current City
* Marital Status
* Product Categories
* Purchase Amount (Target Variable)

---

## Project Workflow

```
Load Dataset
      ↓
Combine Train & Test Data
      ↓
Data Exploration
      ↓
Handle Missing Values
      ↓
Categorical Encoding
      ↓
Feature Engineering
      ↓
Data Type Conversion
      ↓
Exploratory Data Analysis
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Machine Learning Ready Dataset
```

---

## Techniques Used

### Data Preprocessing

* Combined training and testing datasets
* Removed unnecessary identifier columns
* Handled missing values using mode imputation
* Converted categorical variables into numerical representations
* One-hot encoded city categories
* Converted data types for machine learning compatibility

### Feature Engineering

* Binary encoding for Gender
* Ordinal encoding for Age
* One-hot encoding for City Category
* Numerical conversion of Stay in Current City Years

### Exploratory Data Analysis

Visualizations include:

* Age vs Purchase
* Occupation vs Purchase
* Product Category 1 vs Purchase
* Product Category 2 vs Purchase
* Product Category 3 vs Purchase

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Repository Structure

```
black-friday/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── BlackFriday_EDA_FeatureEngineering.ipynb
│
└── README.md
```

---

## Skills Demonstrated

* Exploratory Data Analysis
* Data Cleaning
* Missing Value Treatment
* Feature Engineering
* Categorical Encoding
* Feature Scaling
* Data Visualization
* Machine Learning Data Preparation

---

## Future Work

The processed dataset can be used to develop regression models for predicting customer purchase amounts using algorithms such as:

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor
