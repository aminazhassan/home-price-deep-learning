# Project Proposal

## 1. Project Title
**Home Price Prediction using Deep Learning**

## 2. Problem Statement
The goal of this project is to predict house sale prices using real housing data. House prices depend on many factors such as size, quality, location-related variables, year built, number of rooms, and garage area. This problem is useful because price prediction can help buyers, sellers, real estate agents, and analysts understand how different features affect the final price.

The model will predict the target variable `SalePrice`. This is a supervised regression problem because the output is a continuous numerical value.

## 3. Dataset
The dataset used in this project is the Kaggle **House Prices - Advanced Regression Techniques** dataset.

Dataset source: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

The training data contains house features and sale prices. The dataset includes numerical and categorical variables. Examples of input features include living area, overall quality, year built, garage area, number of bathrooms, and basement size. The output label is `SalePrice`.

Data format: CSV files (`train.csv` and `test.csv`).

## 4. Planned Method
First, I will inspect and clean the dataset. Missing values will be handled using median values for numerical columns and most frequent values for categorical columns. Categorical variables will be converted using one-hot encoding. Numerical features will be scaled for the neural network.

### Baseline Model
The baseline model will be **Linear Regression**. It is simple and useful for comparison.

### Deep Learning Model
The deep learning model will be a **Multilayer Perceptron (MLP)** neural network. It will contain dense layers with ReLU activation and dropout to reduce overfitting.

### Loss Function
The loss function will be Mean Squared Error (MSE).

### Evaluation Metrics
The models will be evaluated using:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### Split Plan
The dataset will be divided into:
- Training set: 80%
- Test set: 20%

## 5. Expected Challenges
One possible challenge is missing values in the dataset. Another challenge is overfitting, because deep learning models can memorize the training data if the model is too complex. Categorical features also need careful preprocessing. In addition, house prices can be affected by many real-world factors that may not be fully represented in the dataset.

## 6. Weekly Plan

| Week | Planned Work | Expected Output |
|---|---|---|
| Week 1 | Dataset selection, repository setup, exploratory data analysis | Proposal, README, dataset summary |
| Week 2 | Data preprocessing, train/test split, baseline model | Baseline results and Week 2 report |
| Week 3 | Deep learning model training and experiments | MLP results, plots, error analysis |
| Week 4 | Improvements, final evaluation, final report and presentation | Final code, final report, slides/demo |
