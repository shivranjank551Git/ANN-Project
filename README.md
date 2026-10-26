# ANN-Project

# Artificial Neural Networks (ANN): Classification and Regression

## Overview
This repository demonstrates the end-to-end implementation of Artificial Neural Networks (ANNs) for two distinct machine learning problems using the same banking  dataset. 
1. **Classification Task:** Predicting customer churn (whether a customer will leave the bank).
2. **Regression Task:** Estimating a customer's salary based on their demographic and financial profile.

## Project Structure
The `ANN-Practical` directory contains all necessary files, notebooks, and saved models for both implementations.

### 📊 Dataset
* **`Churn_Modelling.csv`**: The primary dataset used for both tasks, containing customer data such as Geography, Gender, Credit Score, Age, Balance, and Estimated Salary.

### 📓 Jupyter Notebooks
* **`experiment1.ipynb`**: The **Classification** model. It handles data preprocessing (encoding, scaling) and trains an ANN with a `sigmoid` output layer and `binary_crossentropy` loss to predict the binary `Exited` variable.
* **`salary1.ipynb`**: The **Regression** model. It repurposes the dataset to predict the continuous `EstimatedSalary` variable, utilizing an ANN architecture optimized for regression (typically using a linear activation in the output layer and Mean Squared Error for loss).
* **`hyperparametertunning1.ipynb`**: Implementation of hyperparameter optimization to find the best network architecture, learning rates, and layers.
* **`prediction1.ipynb`**: The inference script that loads the trained models and preprocessing objects to make predictions on new, unseen data.

### 🧠 Saved Models & Preprocessing Objects
These exported files allow the models to be deployed or tested without retraining:
* **`model.h5`**: The trained deep learning model saved in HDF5 format.
* **`scaler.pkl`**: The saved `StandardScaler` used to normalize numerical inputs.
* **`label_encoder_gender.pkl`**: The encoder used to transform the 'Gender' column into numerical values.
* **`onehot_encoder_geo.pkl`**: The encoder used to handle the categorical 'Geography' column.

## Tech Stack
* **Deep Learning Framework:** TensorFlow / Keras
* **Machine Learning:** Scikit-learn
* **Data Manipulation:** Pandas, NumPy
* **Environment:** Jupyter Notebook

## Setup and Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone [https://github.com/shivranjank551Git/ANN-Project.git](https://github.com/shivranjank551Git/ANN-Project.git)


  
