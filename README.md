# Machine-Learning-Learning
# Party Size Prediction (Seaborn Tips Dataset)

This project builds an end-to-end regression pipeline to predict the party size (`size`)
from restaurant bill and context data using Linear Regression.

## Key Concepts Demonstrated
- Train/test split before preprocessing (data leakage prevention)
- Handling numerical and categorical features
- One-hot encoding with reference category
- Feature scaling using StandardScaler
- Model evaluation using Mean Squared Error (MSE)

## Dataset
- Source: Seaborn `tips` dataset
- Target: `size` (number of people at the table)

## Model
- Linear Regression (baseline model)
- Mean Squared Error used for evaluation

## Results
- MSE: ~0.7
- Interpretation: predictions are off by ~0.7 person on average

## Next Improvements
- Polynomial features
- Regularization (Ridge/Lasso)
- Non-linear models
