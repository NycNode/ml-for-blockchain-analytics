
# First ML Model Testing

## Overview

This Jupyter notebook demonstrates a basic machine learning workflow using a Logistic Regression model. The notebook is divided into several key steps, including data loading, preprocessing, model training, and prediction.

## Steps

1. **Import Libraries**: 
    - Import necessary libraries including `pandas`, `sklearn`, and `CountVectorizer`.

2. **Load Dataset**:
    - Load the dataset from `Test_Ethereum_Raw.csv` using `pandas`.

3. **Data Preprocessing**:
    - Use `CountVectorizer` to transform hexadecimal strings into a token frequency matrix.
    - Prepare the target variable using `LabelEncoder`.

4. **Split Dataset**:
    - Split the data into training and testing sets using `train_test_split`.

5. **Train Model**:
    - Initialize and train a Logistic Regression model with the training data.

6. **Randomize Data**:
    - Load `RawTestData.csv` and randomize its first column.
    - Save the randomized data to `RandomizedRawTestData.csv`.

7. **Predict New Data**:
    - Load the randomized data from `RandomizedRawTestData.csv`.
    - Use the trained model to predict the labels for the new data.
    - Save the predictions to `RawPredictions.csv`.

## Requirements

- pandas
- scikit-learn

You can install the required packages using the following command:
```
pip install pandas scikit-learn
```

All the CSV files used in the Jupyter notebook are included in this folder.
