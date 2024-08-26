# Linear_Regression_Height-Weight

## Project Description
Overview
This project explores the relationship between height and weight using a linear regression model. The primary goal is to predict an individual's height based on their weight using a simple linear regression technique.

Goals
To demonstrate the application of linear regression on a real-world dataset.
To evaluate the accuracy of the model in predicting height from weight.

## Installation and Setup
Dependencies
The project requires the following Python libraries:

1. numpy
2. pandas
3. matplotlib
4. seaborn
5. scikit-learn

## Data Description
Dataset Information
The dataset includes the following features:

Weight (kg): The weight of the individuals.
Height (cm): The height of the individuals.

## Methodology
### Approach
A simple linear regression model is used to analyze the relationship between height and weight.
The model was trained using the Scikit-Learn library.
### Feature Engineering
The dataset was scaled using StandardScaler to ensure all features are on the same scale.
### Model Selection
A simple linear regression model was chosen for its simplicity and effectiveness in analyzing the relationship between two continuous variables.
## Results
Model Performance
Slope (Weight Coefficient): 15.01548499
Intercept: 159.64705882
R-squared: The model achieved an R-squared value of 0.86, indicating that 86% of the variance in height is explained by weight.
Visualization
Scatter plots and line graphs were used to visualize the relationship between height and weight.
Interpretation
The results indicate a strong positive linear relationship between height and weight, where an increase in weight is associated with an increase in height.

## Usage
How to Use the Model
To use the trained model for prediction, input a weight value, and the model will output the corresponding height. 

## Conclusions
Summary
The project successfully demonstrates how to apply linear regression to predict height based on weight. The model's strong performance indicates a clear relationship between the two variables.




