# Data-Blitz Competition

This repository consists of the analysis of housing data using Random Forest Regression

There are 6 steps followed in this ML analysis:
1. Load the data
2. Exploratory data analysis (EDA)
3. Pre-processing data (Filling missing values etc)
4. Feature Engineering
5. Modelling
6. Prediction

---------------------------------------------------------------------------------------------------
1. Load the data:
    Data is loaded from housing.csv

2. Exploratory data analysis (EDA):
    General analysis of data is done

3. Pre-processing data (Filling missing values etc):
    null values are updating using imputation
    Ordinal Encoding is used for 'ocean_proximity' feature as it is Categorical data

4. Feature Engineering:
    Extra features like room-per_household & bedroom_per_household are created

5. Modelling:
    Model is created using XGBRegressor

6. Prediction:
    The results of validation data are predicted using the model created
    The accuracy score & rmsc is calculated

---------------------------------------------------------------------------------------------------
