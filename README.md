# House-Price-Prediction-Using-Machine-Learning#

This project presents a comprehensive workflow for predicting house prices using machine learning techniques. Leveraging a dataset containing various features of California housing, the notebook demonstrates data preprocessing, exploratory data analysis, feature engineering, and the implementation of regression models to estimate median house values.

Dataset:
The dataset (housing.csv) includes the following features:

1.longitude: Geographic coordinate (longitude)
2.latitude: Geographic coordinate (latitude)
3.housing_median_age: Median age of houses in the block
4.total_rooms: Total number of rooms per block
5.total_bedrooms: Total number of bedrooms per block
6.population: Population of the block
7.households: Number of households per block
8.median_income: Median income of households in block
9.ocean_proximity: Categorical variable indicating proximity to the ocean
10.median_house_value: Median house value (target variable)

Project Structure:

1.Data Loading and Exploration:
Imports the dataset and performs initial inspection and summary statistics.
2.Data Preprocessing:
Handles missing values, encodes categorical variables (such as ocean_proximity), and creates new features (e.g., bedroom ratio, household rooms).
3.Exploratory Data Analysis (EDA):
Visualizes distributions, relationships, and correlations between variables using libraries like Matplotlib and Seaborn.
4.Feature Engineering:
Adds new features to enhance model performance, such as ratios and one-hot encoding for categorical variables.
5.Model Building:
Implements and evaluates regression models, including:
   1.Linear Regression
   2.Random Forest Regressor

Model Evaluation:
Compares model performance using appropriate regression metrics (e.g., RMSE, MAE).

Requirements:

1.Python 3.x
2.pandas
3.numpy
4.matplotlib
5.seaborn
6.scikit-learn
