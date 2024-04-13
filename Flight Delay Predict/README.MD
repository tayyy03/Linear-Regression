# Delay Flights Prediction

This project is about predicting flight delays using Ridge Regression. The model is trained on a dataset that contains various flight details and the target variable is the delay time.

## Dependencies

- sklearn
- numpy
- pandas

## Usage

The main script is `delay_flights.ipynb`. This script trains a Ridge Regression model on the flight data and evaluates its performance.

The script first imports the necessary libraries:

```python
from sklearn.linear_model import Ridge
from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score
```
Then, it creates a Ridge Regression model with a regularization parameter (alpha) of 5000:
```python
model = Ridge(alpha=5000)
```

The model is then trained on the training data:
```python
model.fit(X_train, y_train)
```

After training, the model makes predictions on the test data:
```python
y_pred = model.predict(X_test)
```

Finally, the script prints out the Mean Squared Error, Mean Absolute Error, and R2 Score of the model:
```python
print('Mean Squared Error:', mean_squared_error(y_test, y_pred))
print('Mean Absolute Error:', mean_absolute_error(y_test, y_pred))
print('R2 Score:', r2_score(y_test, y_pred))
```

## Results
The performance of the model can be evaluated by looking at the Mean Squared Error, Mean Absolute Error, and R2 Score. The goal is to minimize the errors and maximize the R2 Score.

## Future Work
In the future, we can try different models, tune the parameters more, or use more complex feature engineering to improve the performance of the model.
