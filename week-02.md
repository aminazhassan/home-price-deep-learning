# Week 2 Progress Report

## Completed This Week
This week I implemented data preprocessing. Missing values were handled using median values for numerical columns and most frequent values for categorical columns. Categorical variables were converted using one-hot encoding. The dataset was split into training and testing parts.

## Important Files Changed
- `src/train_home_price_models.py`
- `notebooks/home_price_deep_learning_project.ipynb`

## Experiments Run
I trained baseline models such as Linear Regression and Ridge Regression.

## Results So Far
The baseline model gives a first comparison point. The error metrics show how far the predictions are from real house prices.

## Problems or Blockers
Some categorical variables create many one-hot encoded columns, so the feature space becomes larger.

## Plan for Next Week
Next week I will train the deep learning model and compare it with the baseline model.
