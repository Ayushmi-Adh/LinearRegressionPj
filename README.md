# Sonar Data Classification

![04-07-28-574_512](https://github.com/Ayushmi-Adh/LogisticRegressionProject/assets/132826306/0599388a-8345-4fcb-942e-695e713c9af3)


## Overview

This project uses a Logistic Regression model to classify sonar data into two classes: Mines and Rocks. The dataset contains 208 samples with 60 features each. The model is trained on the majority of the data and evaluated on a test set to measure its performance.

## Dataset

The dataset used in this project is "Copy of sonar data.csv." It consists of 208 rows and 61 columns. The target variable (label) is in column 60, with 'M' representing Mines and 'R' representing Rocks.

## Dependencies

- pandas
- numpy
- scikit-learn

Install the dependencies using the following command:

```bash
pip install pandas numpy scikit-learn
```

The script prints the accuracy of the model on both the training and test datasets. Additionally, it includes a predictive system where you can input new data and get a classification result.

## Predictive System

To make predictions for a new object, modify the `input_data` variable with the features of the object. Then run the script, and it will classify the object as a "Rock" or a "Mine."

```python
# Example input_data
input_data = (0.0200, 0.0371, ...)

# Run the script
python sonar_classification.py
```

## Model Evaluation

The accuracy of the model on the training and test datasets is printed during script execution.

