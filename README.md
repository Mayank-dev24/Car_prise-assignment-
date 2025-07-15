Car Price Analysis Project

This project focuses on analyzing a dataset of car specifications to determine how various features affect car prices. The goal is to identify key variables that influence price and clean the data for accurate predictive modeling.

Objectives

- Perform **Exploratory Data Analysis (EDA)**
- Clean and preprocess the dataset
- Handle multicollinearity
- Identify key variables affecting car prices
- Prepare data for modeling

Visualizations
- **Histograms** for distribution
- **Bar Charts** for categorical data
- **Pairplots** for relationships
- **Heatmap** for correlation

 Data Cleaning & Preprocessing

- Removed **redundant columns** ( `carwidth`, `curbweight`, `highwaympg`, `car_stability`)
- Handled **misspellings** in car brand names
- Created **dummy variables** for multi-level categorical columns
- Dropped **ID** columns like `car_ID`

Dataset

-The dataset used in this project is available under:
-data/CarPrice_Assignment.csv

 The required packages installed:

-pandas
-numpy
-matplotlib
-seaborn
