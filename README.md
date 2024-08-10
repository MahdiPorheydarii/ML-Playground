# Car Price Prediction using Regression Models

## Project Overview

This repository contains the final project for the AI course at IUST Industrial Engineering Department. The project's goal is to develop and evaluate a regression model to predict the selling prices of used cars. This project leverages Python and various machine learning libraries to preprocess data, train models, and evaluate their performance.

## Project Structure

- **Report.pdf**: The detailed project report that includes the problem statement, data preprocessing, model development, evaluation, and conclusions.
- **Project_description.pdf**: Project description and expectations.
- **main.ipynb**: The Jupyter Notebook containing the Python code used to preprocess the data, train the models, and analyze the results.
- **cardekho.csv**: The dataset used for model training and evaluation. It contains information on various car features and their corresponding selling prices.
- **LinearRegression.py**: A script implementing the Linear Regression model, one of the models used in this project.

## Project Objective

The primary objective of this project is to create a reliable and accurate tool for predicting the selling price of used cars, which can aid both sellers and buyers in making informed decisions. The model aims to deliver predictions with high accuracy by utilizing regression techniques and improving them based on performance metrics.

## Data Description

The dataset (`cardekho.csv`) includes various attributes related to cars, such as:
- Brand and model
- Year of manufacture
- Mileage
- Engine power
- Fuel type
- Transmission type
- Selling price

## Model Development

### Data Preprocessing
- Handled missing values and removed duplicates.
- Converted categorical variables to numerical values using techniques like one-hot encoding.
- Normalized the data to improve model performance.
- Identified and removed outliers to enhance prediction accuracy.

### Models Used
- **Linear Regression**: Implemented manually.
- **Support Vector Regressor (SVR)**
- **LightGBM Regressor**: Used for comparison with the linear model.

### Evaluation
- Models were evaluated using the Mean Absolute Error (MAE) metric.
- Comparison plots of actual vs. predicted prices were generated to visualize model performance.

## Key Results

- The Linear Regression model provided a baseline performance with an MAE of approximately 58,000 units.
- SVR and LightGBM models were also tested, with LightGBM showing the best performance among the models tested but not so different with our LR model.
- Suggestions for model improvement include increasing the dataset size, adding more relevant features, tuning model hyperparameters, and experimenting with more complex models like Deep Neural Networks.

## Conclusion

This project demonstrates the application of linear regression techniques for predicting car prices, highlighting the importance of data preprocessing and model evaluation in achieving reliable predictions. The tools and methods used in this project can be further refined for deployment in a real-world car sales platform.

## License
This project is licensed under the MIT [License](LICENSE).

## Acknowledgments

While the methods and models implemented in this project provide a foundational approach to predicting car prices, they are not intended to be the most accurate or comprehensive solution. The content and techniques used here are designed to suffice for the purpose of demonstrating the project requirements.

There are more advanced and effective ways to predict car prices that involve deeper data analysis, more sophisticated models, and larger datasets. The methods presented in this project should be considered as a basic introduction to the topic rather than a definitive guide.
