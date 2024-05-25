# Electric Vehicle Range Analysis Using Machine Learning Techniques

## Overview

This project focuses on analyzing and predicting the electric range of vehicles using various machine learning techniques. We explore and visualize data, apply regression, classification, and clustering methods, and interpret the results to understand key factors influencing electric vehicle range.

## Table of Contents

- [Introduction](#introduction)
- [Data Description](#data-description)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling Techniques](#modeling-techniques)
  - [Linear Regression](#linear-regression)
  - [Decision Tree Regression](#decision-tree-regression)
  - [KMeans Clustering](#kmeans-clustering)
  - [Random Forest Classification](#random-forest-classification)
- [Results](#results)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Introduction

The aim of this project is to utilize machine learning techniques to analyze the electric range of vehicles and identify the key factors that influence it. We employ various models to predict and classify electric ranges based on vehicle characteristics such as model year and MSRP.

## Data Description

The dataset includes various features of electric vehicles, such as:

- VIN (1-10)
- County, City, State
- Make, Model
- Electric Vehicle Type
- Clean Alternative Fuel Vehicle (CAFV) Eligibility
- Vehicle Location
- Electric Utility
- Postal Code
- Model Year
- Electric Range
- Base MSRP
- DOL Vehicle ID
- 2020 Census Tract

## Exploratory Data Analysis (EDA)

We perform EDA to understand the distribution and relationships of the data. Key steps include:

- Visualizing distributions using box plots
- Understanding the spread and central tendencies of numerical features
- Identifying outliers

## Modeling Techniques

### Linear Regression

We apply linear regression to predict the electric range based on 'Model Year' and 'Base MSRP'. The results are visualized using scatter plots to compare actual vs. predicted values.

### Decision Tree Regression

A decision tree regressor is used to predict electric range. The tree structure helps identify key decision points and feature importance.

### KMeans Clustering

KMeans clustering is applied to group vehicles based on 'Model Year' and 'Electric Range'. The clusters help understand the segmentation of vehicles by these features.

### Random Forest Classification

We use a Random Forest Classifier to predict whether a vehicle has a high electric range. The feature importance plot highlights the significance of 'Model Year' and 'Base MSRP'.

## Results

- **Linear Regression**: Captures general trends but struggles with extreme values.
- **Decision Tree Regression**: Identifies key decision points but may overfit with limited depth.
- **KMeans Clustering**: Reveals distinct vehicle segments based on model year and range.
- **Random Forest Classification**: 'Model Year' is the most critical predictor of electric range.

## Conclusion

The analysis demonstrates that 'Model Year' significantly impacts the electric range of vehicles. Machine learning models provide valuable insights and can predict electric ranges with reasonable accuracy, though model performance varies across techniques.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/electric-vehicle-range-analysis.git
   cd electric-vehicle-range-analysis
