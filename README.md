# House Price Prediction

A beginner regression project using scikit-learn to predict the sale price of a house based on its features.

## What this project does

I loaded a dataset of 1,500 houses, explored it with some basic plots, and trained a Linear Regression model to predict house prices.

## Libraries used

- `pandas` — loading and exploring the data
- `matplotlib` — basic plots
- `scikit-learn` — train/test split, Linear Regression, evaluation metrics

## How to run

1. Make sure you have the libraries installed:
```bash
pip install scikit-learn pandas matplotlib numpy
```

2. Place `house_prices_dataset.csv` in the same folder as the notebook

3. Open the notebook:
```bash
jupyter notebook project2_house_price.ipynb
```

## Results

- **Model:** Linear Regression
- **R² Score:** ~0.82
- **RMSE:** ~$68,000
- Most influential features: `sqft`, `neighborhood`, `condition`

## Files

```
├── project2_house_price.ipynb
├── house_prices_dataset.csv
└── README.md
```
