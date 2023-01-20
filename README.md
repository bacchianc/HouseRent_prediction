# Regression_project
Decision Tree Regressor, Rnadom Forest Regressor, House Rent Prediction
# Machine Learning Model to predicts the monthly rental of a house 

1. Introduction
This project focuses on building a model to predict monthly rental of a house.

The value of a house is more than just location and square footage. Houses have several features that make up it's value.We are going to take advantage of all the features to make accurate predictions about the rent of any house.

Algorithm used:
Decision Tree, GridSerachCV,Linear Regression

Features:
Id: listing id url: listing URL region: craigslist region region_url: region URL type: housing type sqfeet: total square footage beds:number of beds baths:number of bathrooms cats_allowed: cats allowed boolean (1 = yes, 0 = no) dogs_allowed: dogs allowed boolean smoking_allowed: smoking allowed boolean wheelchair_access: has wheelchair access boolean electric_vehicle_charge: has electric vehicle charger boolean comes_furnished: comes with furniture boolean laundry_options: laundry options available parking_options: parking options available image_url: image URL description: description by poster lat: latitude long: longitude state: state of listing

Target:
Monthly rent of the House

2. Solution approach Using Decision Tree Regressor
2.1 Import Necessary Libraries

2.2 Loading the House Price Dataset

2.3 Take a Quick Look at the Data Structure

2.4.Selecting Features to a Model Build

2.5 Information About Data

2.6 Data Preprocessing (Analysis (EDA))

2.7 Dealing with Outliers

2.8 Filtering Categorical Data

2.9 Dividing the Dataset into Features and Label

2.10 Checking the relationship of Features with Label

2.12 Checking for the multicollinearity in Features

2.13 Data splitting for training the Model

2.14 Building a Model Using The Decision Tree Regressor

2.15 Calculating the Accuracy of Model
