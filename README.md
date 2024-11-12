Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

# Housing Price Prediction
This repository contains Python code for predicting house prices based on features such as area, number of bedrooms, and number of bathrooms. The code uses linear regression as the machine learning model and performs outlier analysis and treatment to improve the model's accuracy.

## Requirements
Make sure you have the following libraries installed:
- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn



## Function

The script will perform the following steps:
- Load the dataset (`train.csv`) into a pandas DataFrame.
- Clean the data by checking for and handling null values.
- Perform outlier analysis and treatment for the 'Price' and 'Area' variables.
- Split the data into training and testing sets.
- Train a linear regression model on the training data.
- Evaluate the model's performance using the \( R^2 \) score.
- Visualize the relationship between real and predicted house prices.
