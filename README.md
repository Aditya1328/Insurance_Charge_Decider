# Deciding Insurance Charges with Machine Learning

This project focuses on building a machine learning model to predict insurance charges based on various customer features such as age, sex, BMI, number of children, smoking status, and region. The end goal is to accurately forecast the cost of insurance for individuals.Insurance companies use various factors to determine how much a person should be charged for health insurance. These factors often include demographics and health-related metrics. Using supervised machine learning, this project develops a model that can predict the insurance premium cost for a customer based on historical data.

## - Handling Missing Values:- 
Object-type columns are filled with their mode, while numeric columns are filled with their mean using a conditional loop.

## - Removing Duplicates:- 
Identifies and removes duplicate rows.

## - Outlier Detection and Removal:- 
Calculates the Interquartile Range (IQR) for selected columns. Outliers are removed based on lower and upper bounds.

## - Boxplot Visualization:- 
Boxplots are generated for all numeric columns to visually inspect outliers.

## - Label Encoding:- 
Converts categorical columns to numerical values using LabelEncoder.

## - Data Split for Training and Testing:- 
Splits the dataset into training and testing sets using train_test_split with 80% training data and 20% testing data.

## - Model Training:- 
A linear regression model is trained using LinearRegression.

## - Performance Evaluation:- 
The model's performance is assessed using r2_score. A regression plot is generated to visualize the fit between predicted and actual values.




