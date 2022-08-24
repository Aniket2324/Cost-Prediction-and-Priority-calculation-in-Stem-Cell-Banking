Cost Estimation


About


To calculate cost for stem cell insurance for different patients.


Getting Started


1. Install all the dependencies.
     pip install numpy
     pip install pandas
     pip install -U scikit-learn


2. Import all the Dependencies
     import numpy as np
     import pandas as pd
     import matplotlib.pyplot as plt
     import seaborn as sns
     from sklearn.model_selection import train_test_split
     from sklearn.linear_model import LinearRegression
     from sklearn import metrics




3. Loading the data from csv file to a Pandas DataFrame
4. Check for missing values in the dataset
5. Plot histograms for different columns to analyze the data
6. Encoding the categorical features
# encoding sex column
insurance_dataset.replace({'sex':{'male':0,'female':1}}, inplace=True)


3 # encoding 'smoker' column
insurance_dataset.replace({'smoker':{'yes':0,'no':1}}, inplace=True)


# encoding 'region' column
insurance_dataset.replace({'region':{'southeast':0,'southwest':1,'northeast':2,'northwest':3}}, inplace=True)


7. Split the data into features and a target.
8. Split the data into Training data & Testing Data
9. Then train and evaluate the model
10. Calculate cost on both training data and testing data
11. Calculate the r square value for both the values
12. Now, take input from users for different patients to calculate their insurance cost.