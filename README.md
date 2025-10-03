# Real Estate Price Prediction
## Description:

This project uses machine learning techniques to predict the prices of properties based on various features, including area and the number of bedrooms. The goal is to build a model that can estimate property prices with high accuracy, leveraging data pre-processing, feature selection, and model optimization techniques.

## Steps Involved:

### Data Preprocessing:

The dataset (property.csv) is loaded, filtered for properties in Islamabad, and missing values in key columns (e.g., agency, agent) are filled with the mode value.

The date_added column is converted to a datetime format to facilitate analysis.

### Exploratory Data Analysis (EDA):

A basic analysis of the dataset is performed, including checking for missing values and visualizing the distribution of prices and key features.

Correlation analysis is conducted to examine relationships between features.

### Feature Selection:

The relevant features (area_sq_meter, bedrooms) are selected as predictors for the target variable (price).

### Model Training:

A Random Forest Regressor model is trained on the data, with hyperparameters optimized using Grid Search and 5-fold cross-validation.

Hyperparameters such as n_estimators, max_depth, min_samples_split, and min_samples_leaf are tuned to improve the model's performance.

### Model Evaluation:

The best model is evaluated based on the training set using mean squared error (MSE) and other relevant metrics.

### Prediction:

Once trained, the model predicts property prices based on the selected features, providing accurate price estimates for the test set.

## Key Features:

Data Preprocessing: Handles missing values and converts columns to appropriate formats.

Model Optimization: Uses GridSearchCV to find the best Random Forest model with hyperparameter tuning.

Model Evaluation: Evaluates the model’s performance using mean squared error (MSE).
