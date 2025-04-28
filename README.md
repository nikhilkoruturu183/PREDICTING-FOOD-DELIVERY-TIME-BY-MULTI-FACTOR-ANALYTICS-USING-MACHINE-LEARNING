# Predicting Food Delivery Time by Multi-Factor Analytics Using Machine Learning

## Overview

The project aims to predict the time for delivering food by analyzing the factors associated with the food delivery system (such as weather conditions, traffic conditions, delivery locations etc.) with the implication of machine learning.

## Features

1. **Data Reading:**
   - The data has been collected from Kaggle and stored in directory (device).
   - The data has been read using Python.
   - Data cleaning process has been applied to clean the missisng values.

2. **Data Analysis and Visualization (EDA):**
   - The analyses of the features have been presented through grapgs in the form of a dashboard.

3. **Preprocessing Data:**
   - Data encoding has been employed to convert the object type features to numerical features.
   - The data noise have been cleaned with the application of PCA and data scaling techniques.
   - The chi-squared method has been used for feature selection.

4. **Data Preparation:**
   - The predictor data has been prepared by taking the selected features into concern.
   - The train and test data have been prepared through splitting the data by 75%-25% ratio.

5. **Model Preparation Through Hyperparameter Tuning:**
   - The hyperparameters of the selected models have been tuned using the GridSearch method.
   - The meta-learning model has been designed by taking two top models as got from the tuning score results.

6. **Food Delivery Time Prediction:**
   - The prediction of food delivery time has been done with the application of the tuned models.
   - The performances of the models have been compared using regression metrics such as Train R2, Test R2, MSE, MAPE etc.

7. **Result Visualization:**
   - The performances of the models have been visualized through graphs using bar charts.

## Requirements

The project requires Python 3.9 or above and the following Python libraries:

- `warnings`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

Install dependencies using the following command:
```
pip install numpy pandas matplotlib seaborn scikit-learn



```python

```
