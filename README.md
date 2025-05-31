# Task3
# Day 3: Simple and Linear Regression 

## Objective

To implement and understand **Simple and Linear Regression** using the Titanic dataset. This task includes data preprocessing, model training, evaluation, and visualization.

---

## Dataset

- Dataset: Titanic Dataset 
- File Used: `train.csv`
- Target for Regression: `Fare`
- Feature: `Age`

---

## Steps Followed

### 1. Import and Preprocess the Dataset

- Loaded the dataset using `pandas`
- Selected relevant numeric features: `Age` and `Fare`
- Handled missing values using `.dropna()`

### 2. Split Data into Train-Test Sets

- Used `train_test_split` from `sklearn.model_selection`
- 80% training, 20% testing

### 3. Fit a Linear Regression Model

- Imported `LinearRegression` from `sklearn.linear_model`
- Trained the model on training data (`X_train`, `y_train`)

### 4. Evaluate the Model

- Evaluated the model using:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² Score
- Used functions from `sklearn.metrics`

### 5. Visualize Regression Line

- Plotted regression line using `matplotlib`
- Plotted actual vs predicted values to interpret the model fit

