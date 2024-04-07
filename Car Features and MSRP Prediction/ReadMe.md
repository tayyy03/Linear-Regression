# Car Features and MSRP Prediction

This project is about predicting the Manufacturer's Suggested Retail Price (MSRP) of cars based on their features.

## Dependencies

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Data
The data used in this project is a CSV file containing information about various cars and their features. The target variable is the Manufacturer's Suggested Retail Price (MSRP).
https://www.kaggle.com/datasets/CooperUnion/cardataset/data

## Methodology
The project uses various regression models from the scikit-learn library to predict the MSRP of cars based on their features. The models used include Linear Regression, Ridge Regression, Lasso Regression, K-Nearest Neighbors, Neural Network, Support Vector Machines, Decision Tree, Random Forest, and Gradient Boosting.

The data is first split into a training set and a test set using the train_test_split function from scikit-learn. Each model is then trained on the training set and evaluated on the test set.

## Results
The performance of each model is evaluated using the Mean Squared Error (MSE) between the predicted and actual MSRP values.

## Usage
To run the project, first install the dependencies, then run the Jupyter notebook:
```bash
jupyter notebook Car\ Features\ and\ MSRP.ipynb
```
