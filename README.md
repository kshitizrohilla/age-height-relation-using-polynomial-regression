# Age and Height Relation using Polynomial Regression
This project explores the relationship between age and height using polynomial regression. The data used in this project is given in the CSV file named age-height-data.csv.

## Requirements
* Python 3
* NumPy
* pandas
* scikit-learn
* matplotlib

## Installation
Install Python 3 by following the instructions on the official website: https://www.python.org/downloads/

Install the required Python packages using pip:
```
pip install numpy pandas scikit-learn matplotlib
```

## Methodology
The script performs the following steps:

* Load the data from the age-height-data.csv file using pandas.

* Preprocess the data by splitting it into input (age) and output (height) variables, and reshaping them to fit the input requirements of scikit-learn.

* Define the polynomial degree as 2 and transform the input variable to include polynomial features using scikit-learn's PolynomialFeatures class.

* Fit the polynomial regression model using scikit-learn's LinearRegression class.

* Generate predictions over a range of age values to plot the line of best fit.

* Plot the data and the line of best fit using matplotlib.

## Results
The script generates a plot showing the data and the line of best fit, which represents the relationship between age and height according to the polynomial regression model.

The results can be used to understand the relationship between age and height and make predictions about height based on age.