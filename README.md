# House-price-prediction

## Overview
This project aims to predict house prices using machine learning techniques. The dataset used is the California Housing dataset, which contains various features such as population, median income, median house value, etc.

## Requirements
Python 3.x
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Clone the repository:
git clone https://github.com/Electrolight123/house-price-prediction.git

## Dataset
The dataset used in this project is the California Housing dataset. It contains various features such as median income, housing median age, average rooms, average bedrooms, population, households, etc.

## Model
Two machine learning models are trained in this project:

Linear Regression
Random Forest Regressor

## Results
After training and evaluating the models, the Random Forest Regressor outperformed the Linear Regression model with a higher R-squared score on the test dataset.

The provided code demonstrates using a potentially trained Random Forest model (best_forest) to predict the price of a house with specific features:

### print(best_forest.predict([[-122.23, 37.88, 41, 880, 129, 322, 126, 8.3252, 0, 0, 0, 1, 0, 0.146, 6.984]]))
Use code with caution.
This assumes you have already trained and saved the best_forest model.

Note: Replace the feature values in the list with the actual features of the house you want to predict the price for. The meaning and order of these features should correspond to your dataset.
