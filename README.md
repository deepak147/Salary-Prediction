# Machine Learning Pipeline for Salary Prediction

This Jupyter Notebook contains a machine learning pipeline for predicting salary using a dataset from `train.csv`.

## Introduction

This notebook demonstrates the process of building and evaluating a machine learning model for classification. It covers the following steps:

1. Data Loading and Exploration
2. Data Preprocessing
3. Model Training and Evaluation
4. Model Serialization

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

## Usage

1. Ensure you have the necessary dependencies installed.
2. Open the Jupyter Notebook.
3. Execute each cell sequentially to follow along with the process.
4. Modify the code as needed for your specific use case.
5. Save the trained model for later use.

## Notebook Contents

- **Data Loading and Exploration**: Loads the dataset from `train.csv` and performs basic exploration using pandas.
- **Data Preprocessing**: Handles missing values and categorical features.
- **Model Training and Evaluation**: Trains a classification model using scikit-learn's `Pipeline` and evaluates its performance.
- **Model Serialization**: Serializes the trained model using `pickle` for later use.

## File Structure

- `train.csv`: Input dataset containing training data.
- `pipeline.pickle`: Serialized model file.

## Acknowledgments

- This notebook utilizes pandas for data manipulation and scikit-learn for machine learning tasks.
- The model is trained using scikit-learn's `Pipeline` for ease of use and reproducibility.
- Model serialization is done using Python's `pickle` module.
