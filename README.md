# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

## In this homework assignment, I will:

## Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

## Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

## Reporting

For this assignment I decided on a Logistic Regression model and a Support Vector Machines (SVC/SVM) Model. For my analysis, I decided to test each model's prediction capabilities by producing a new dataframe, showing a subset of the actual vs the predicted values of the original dataset. Then I created a confusion matrix using seaborn, which helped visualize the importance of "false" positives and negatives that the model showed in the predicted dataset. I also calculated the testing data score of each model, to see the accuracy percentages. For logistic regression, there was a score of **83.3%**, and for the SVC model, there was a score of **84.2%**. In conclusion, both models did relatively decent in predicting exoplanets, but these could both use some fine tuning to up the accuracy percentages. I initially decided not to remove any columns in the original dataset, as I wanted to utilize the full range of variables given, but I think for a future comparison, I will definitely clean up the dataset more before implementing more ML models. 
