# Predict Household Energy Consumption

This project aims to predict household energy consumption based on time-series data.

## Code Overview

The code first trains a `StandardScaler` on the feature data `X`. This scaler is then used to standardize the features of each row in `X`.

The standardized features are then fed into a pre-trained model to predict the household energy consumption. The predictions are stored in a list, which is then converted into a DataFrame for easier manipulation and visualization.

The first few rows of the actual and predicted energy consumption are printed to the console for quick inspection.

Finally, the actual and predicted energy consumption for the first 500 time points are plotted for visual comparison.

## Code Usage

To use this code, you need to have a pre-trained model stored in the variable `model`, and your feature and target data stored in `X` and `y` respectively.

## Dataset
https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set/data

## Dependencies

This code depends on the following Python libraries:

- pandas
- numpy
- matplotlib
- sklearn

## Future Work

Future work could include calculating evaluation metrics for the predictions, such as Mean Absolute Error (MAE), Mean Squared Error (MSE), or Root Mean Squared Error (RMSE).
