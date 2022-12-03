# Supevised Machine Learning: Predict Housing Prices
create a model that predicts the price of a house based on its characteristics. Create a model to predict whether a house is expensive or not. Create a model to predict the exact price of a house.

![grafik](https://user-images.githubusercontent.com/100354393/205448241-bb12af70-f0fc-4466-935c-fa4f7714934f.png)

# Goal
The task is to create a model that predicts the price of a house based on its characteristics
The project will be divided into two major phases:
1. Create a model to predict whether a house is expensive or not. 
2. Create a model to predict the exact price of a house.


# Data Set 
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's analternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 
This Dataset is used in the following Kaggle Competition: 
> "House Prices - Advanced Regression Techniques. Predict sales prices and practice feature engineering, RFs, and gradient boosting"

The dataset contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa
The datsate contains the prices and explanatory variables for a sample of 1460 houses. 

[Here you can find the dataset and also an overview of the competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

# Skills/Methods
- Creative feature engineering 
- Advanced regression techniques like random forest and gradient boosting
- Implementation with scikit-learn
- 

## Basic Steps in this Project: 

![grafik](https://user-images.githubusercontent.com/100354393/205448382-c7258c89-05cf-4d90-ae76-f30fe592669d.png)

1. Explore & clean the data 
2. Data preprocessing
3. Modelling 
4. Model Tuning using GridSearch in combination with Cross Validation
5. Model Evaluation      
--> [Associated Notebook for classification task: Predicting if house is expensive or not](../main/housing_prices_model_classification.ipynb)      
--> [Associated Notebook for regression task](../main/housing_prices_model_regression.ipynb)  
5. Further exploratuons: Performance after dimensionality reduction with PCA 
--> [Associated Notebook](../main/housing_prices_regression_pca.ipynb) 
4. Further explorations: Feature selection techniques 
--> [Associated Notebook](../main/feature_selection_housing_prices.ipynb) 
5. Take part at kaggle competion
--> [Associated Noteboook](../main/kaggle_competition_feature_selection_housing_prices_model.ipynb)


## Files in this repository
- [Description of the features](../main/data_description.txt)

### to do: 
- merge the two files for the project under 4. in basic steps
- adapt the way the dataset is loaded by putting the datase in my google drive
