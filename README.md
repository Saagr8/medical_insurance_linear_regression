# Medical Insurance Cost Prediction using Linear Regression

## About This Project

In this project, I practised Linear Regression using a medical insurance dataset.

The goal was to predict insurance charges based on information like age, BMI, smoking status and other features.

I also tried different ways to improve the model and compared the results.

## What I Did

- Loaded and explored the dataset using Pandas.
- Used Seaborn to visualise the relationship between BMI, insurance charges and smoking.
- Converted categorical data into numerical values.
- Split the dataset into training and testing data.
- Trained a Linear Regression model.
- Evaluated the model using R² and adjusted R².
- Used one-hot encoding and interaction features to improve the model.

## Model Results

I tried three different versions of the model.

| Model | Test R² Score |
|---|---|
| Basic Linear Regression | 0.781 |
| With Region Encoding | 0.784 |
| With Interaction Features | 0.865 |

The model with interaction features performed the best on the test data.

## Tools Used

- Python
- Pandas
- Seaborn
- Scikit-learn
- Jupyter Notebook

## What I Learned

This project helped me practise Linear Regression and understand how different features can affect a model's predictions.

I also learned how to use R² scores to compare models and why it is important to check both training and testing results.

## Files

- `linear_regression.ipynb` — My code and model experiments.
- `insurance.csv` — Dataset used for this project.