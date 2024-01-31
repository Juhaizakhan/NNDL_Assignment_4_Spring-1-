# Data Analysis and Linear Regression Documentation

## 1. Data Analysis

### Overview
The data analysis script reads a CSV file containing data related to exercise and health metrics. It performs various data manipulation tasks and generates a scatter plot to visualize the relationship between exercise duration and calories burned.

### Steps
1. Read Data: Reads the provided CSV file containing exercise and health metrics using pandas.
   
2. Data Description: Computes basic statistical descriptions of the data such as mean, standard deviation, minimum, maximum, etc.

3. Handling Null Values: Checks for null values in the dataset and replaces them with the mean value of their respective columns.

4. Filtering Data: Filters the dataset to select rows with calories values between 500 and 1000, as well as rows with calories greater than 500 and pulse less than 100.

5. Scatter Plot: Creates a scatter plot to visualize the relationship between exercise duration and calories burned.

## 2. Linear Regression

### Overview
The linear regression script reads a CSV file containing salary data and performs linear regression to predict salary based on years of experience. It splits the data into training and testing sets, trains a linear regression model, and evaluates its performance.

### Steps
1. **Read Data:** Reads the provided CSV file containing salary data using pandas.

2. **Data Splitting:** Splits the data into training and testing sets using scikit-learn's train_test_split function.

3. **Model Training:** Trains a linear regression model using scikit-learn's LinearRegression class.

4. **Prediction:** Predicts salary values for both the training and testing sets.

5. **Model Evaluation:** Calculates the mean squared error (MSE) to evaluate the performance of the model.

6. **Visualization:** Visualizes both the training and testing data along with the regression line to observe the relationship between years of experience and salary.
