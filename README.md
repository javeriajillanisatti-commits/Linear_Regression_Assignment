# Linear Regression Machine Learning Project

## Project Overview

This project focuses on building and evaluating a Linear Regression model using Python and Scikit-learn. The main purpose of this project is to understand the complete machine learning workflow, including data loading, preprocessing, model training, evaluation, visualization, and improving model performance.

Different techniques were applied to analyze the model behavior and understand how different settings affect prediction accuracy.

---

## Dataset Information

- **Dataset Name:** Insurance Dataset
- **Problem Type:** Regression Problem

The dataset contains different features that are used to predict the target value. Before applying the model, the dataset was cleaned and prepared for machine learning.

---

## Tasks Performed

### 1. Data Loading and Preprocessing

- Loaded the raw CSV dataset.
- Checked the dataset structure and available features.
- Handled missing values to improve data quality.
- Encoded categorical columns into numerical form before modeling.
- Prepared the dataset for machine learning.

---

### 2. Data Splitting

- Divided the dataset into training and testing sets.
- Used different train-test split ratios:
  - 60% Training / 40% Testing
  - 80% Training / 20% Testing
  - 90% Training / 10% Testing

- Compared the effect of different split ratios on model performance.

---

### 3. Linear Regression Model Training

- Built a Linear Regression model using Scikit-learn.
- Trained the model using training data.
- Used the trained model to make predictions on unseen test data.

---

### 4. Model Evaluation

The model was evaluated using different performance metrics:

- **Mean Squared Error (MSE)**
  - Measures the difference between actual and predicted values.
  - Lower MSE represents better prediction performance.

- **R² Score**
  - Shows how well the model explains the relationship between input features and target values.
  - Higher R² score indicates better model performance.

---

### 5. Model Visualization

- Created graphs to analyze model predictions.
- Plotted actual values versus predicted values.
- Used visualization to understand how closely predictions match the real data.

---

### 6. Cross Validation

- Applied K-Fold Cross Validation using Scikit-learn's `cross_val_score`.
- Divided the dataset into multiple folds for better model evaluation.
- Calculated the average validation score to measure model performance.

---

### 7. Learning Curve Analysis

- Created a learning curve by comparing:
  - Training score
  - Testing score

- Used the learning curve to analyze:
  - Overfitting
  - Underfitting
  - Model generalization

---

### 8. Code Refactoring

The notebook code was organized into reusable functions:

- `load_data()`
  - Loads the dataset.

- `split_data()`
  - Splits data into training and testing sets.

- `train_model()`
  - Trains the Linear Regression model.

- `evaluate_model()`
  - Calculates model performance metrics.

This improved code readability and made the workflow easier to reuse.

---

### 9. Polynomial Regression

- Extended the Linear Regression model using Polynomial Features.
- Applied Degree 2 Polynomial Regression.
- Compared Polynomial Regression performance with the basic Linear Regression model.
- Analyzed whether the polynomial model:
  - Overfits
  - Underfits
  - Generalizes better

---

## Libraries and Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

### Linear_Regression.ipynb

This notebook contains the complete implementation of the Linear Regression project. It includes:

- Loading and preparing the dataset
- Handling missing values
- Encoding categorical features
- Splitting data into training and testing sets
- Training the Linear Regression model
- Model evaluation using MSE and R² score
- Visualization of actual vs predicted values
- Train/test split ratio comparison
- K-Fold Cross Validation
- Learning curve analysis
- Code refactoring using reusable functions
- Polynomial Regression comparison

## Learning Outcomes

After completing this project, the following concepts were learned:

- Understanding the complete workflow of a machine learning project.
- Loading and preparing a raw dataset for modeling.
- Handling missing values and converting categorical data into numerical form.
- Understanding how Linear Regression works for prediction tasks.
- Training a machine learning model using Scikit-learn.
- Evaluating model performance using Mean Squared Error (MSE) and R² Score.
- Understanding the effect of different train-test split ratios on model performance.
- Using K-Fold Cross Validation for better model evaluation.
- Analyzing learning curves to identify overfitting and underfitting.
- Improving code structure by creating reusable functions.
- Understanding the effect of polynomial features on model complexity and performance.

---
## Conclusion

This project demonstrates the complete implementation of a Linear Regression model, starting from data preprocessing to model evaluation and improvement. Different techniques were applied to analyze model performance, improve reliability, and understand how changes in data splitting and model complexity affect prediction results.