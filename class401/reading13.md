# Class 13

[Back to home page](../README.md)

## Linear regressions

Q. Can you explain the basic concept of linear regression and its purpose in the context of machine learning and data analysis?

- Linear regression is the concept of finding the average line form in a scatter plot of data, or the average amoung the data. It models the relationship between a dependant variable and one or more independant variables. Using this method, the user will be able to predict the value of the dependant variable from the values of the independant variables.

Q. Describe the process of implementing a linear regression model using Python’s Scikit Learn library, including the necessary steps and functions.

1. import the packages and classes needed
2. Create a numpy array with data
3. Create an instance of a linear regression model and fit it to the data with the fit() function
4. Obtain the coefficient of determination by calling the model with the score() function, then print the coefficient
5. print the results (intercept, slope)
6. predict a response

Q. What is the purpose of splitting the dataset into train and test sets, and how does this contribute to the evaluation of a machine learning model’s performance?

- The purpose is to evaluate the performance of a machine learning model. The training set is used to train the machine learning model, while the test set is used to assess the performance of the machine after training.

## Bookmark and review

- [Train & Test Splits](https://towardsdatascience.com/train-test-split-and-cross-validation-in-python-80b61beca4b6)

- [What is Linear Regression](https://www.statisticssolutions.com/what-is-linear-regression/)
