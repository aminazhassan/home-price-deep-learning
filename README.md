# Home Price Prediction using Deep Learning

## Project Overview
This project predicts house sale prices using the Kaggle **House Prices - Advanced Regression Techniques** dataset.  
The task is a supervised regression problem: the model uses house features such as area, quality, year built, rooms, and other numerical/categorical variables to predict `SalePrice`.

## Dataset
Dataset source: Kaggle House Prices - Advanced Regression Techniques  
Kaggle link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

Files needed:
- `train.csv`
- `test.csv`
- `data_description.txt`

Do not commit large raw dataset files to GitHub. Download them from Kaggle and place them in the `data/` folder locally, or run the notebook directly on Kaggle.

## Repository Structure
```text
project-repo/
├── README.md
├── data/
│   └── README.md
├── notebooks/
│   └── home_price_deep_learning_project.ipynb
├── src/
│   └── train_home_price_models.py
├── reports/
│   ├── proposal.md
│   ├── week-01.md
│   ├── week-02.md
│   ├── week-03.md
│   └── week-04.md
├── results/
├── requirements.txt
├── final-report.md
└── presentation-script.md
```

## Models
1. Baseline model: Linear Regression
2. Machine learning comparison: Ridge, Random Forest, Gradient Boosting
3. Deep learning model: MLP Neural Network

## Metrics
- MAE
- RMSE
- R² Score

## How to Run
Install requirements:
```bash
pip install -r requirements.txt
```

Run script:
```bash
python src/train_home_price_models.py
```

Or open:
```text
notebooks/home_price_deep_learning_project.ipynb
```

## Notes
If running on Kaggle, the dataset path is:
```text
/kaggle/input/home-data-for-ml-course/train.csv
```

If running locally, put `train.csv` inside the `data/` folder.
