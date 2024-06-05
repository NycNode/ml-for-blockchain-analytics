
# First Embedding ML Model Testing

## Overview

This Jupyter notebook demonstrates a machine learning workflow using Logistic Regression with PCA (Principal Component Analysis) for dimensionality reduction. The notebook includes data loading, preprocessing, PCA transformation, model training, evaluation, and prediction.

## Steps

1. **Import Libraries**: 
    - Import necessary libraries including `pandas`, `sklearn`, and `PCA`.

2. **Load Dataset**:
    - Load the dataset from `LatestDataSet.csv` using `pandas`.

3. **Shuffle Dataset**:
    - Shuffle the dataset to ensure randomness.

4. **Extract Features and Labels**:
    - Extract embeddings and labels from the dataset.

5. **Apply PCA**:
    - Apply PCA to reduce the dimensionality of the embeddings.

6. **Split Dataset**:
    - Split the data into training and testing sets using `train_test_split`.

7. **Train Model**:
    - Train a Logistic Regression model with the training data.

8. **Make Predictions**:
    - Use the trained model to make predictions on the test set.

9. **Evaluate Model**:
    - Evaluate the model's performance using accuracy score and confusion matrix.

10. **Save Predictions**:
    - Add predictions as a new column to the original data.
    - Save the updated DataFrame to `newoutput.csv`.

## Requirements

- pandas
- scikit-learn

You can install the required packages using the following command:
```
pip install pandas scikit-learn
```

All the CSV files used in the Jupyter notebook are included in this folder.
