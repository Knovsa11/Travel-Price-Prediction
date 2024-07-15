# Travel-Price-Prediction

This project is designed to create a regression model to predict or forecast ride-hailing platform trip prices. The dataset used is sourced from Kaggle with the name Uber and Lyft Dataset Boston (https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma) Ma which contains information about all Uber trips and Lyft is carried out in the City of Boston. The R² score obtained was 0.90, and the MAE was 1.74 based on the regression model.

## Project Purpose
The main purpose of this project is to develop a reliable regression model to predict trip prices on ride-hailing platforms like Uber and Lyft. By accurately estimating trip costs, users can make informed decisions, and service providers can optimize their pricing strategies.

## Problem Statement
Determining the price of ride-hailing trips is complex due to various influencing factors such as distance, time of day, traffic conditions, and service type. This project aims to address this complexity by creating a predictive model that accurately estimates trip prices, thereby providing valuable insights for both users and service providers.

## Background
Ride-hailing services like Uber and Lyft have transformed urban transportation by offering convenient and flexible travel options. However, the dynamic pricing models used by these platforms can lead to price variations, making it challenging for users to predict trip costs. By analyzing historical trip data, this project seeks to understand the factors influencing trip prices and develop a model to predict future trip costs accurately.

## Project Output

The output of this project includes:
A trained regression model to predict trip prices on ride-hailing platforms.
Insights into the factors that significantly influence trip prices.
Performance metrics of the model, including R² and MAE scores.

## Methods
The project utilizes the following methods:

Exploratory Data Analysis (EDA): Understanding the dataset and identifying patterns and trends.
Feature Engineering: Creating and selecting features that improve model performance.
Modeling: Building and training the regression model using various algorithms.
Evaluation: Assessing the model's performance using metrics like R² and MAE.

## Technology Stack
The project is developed using the following technologies:

Programming Language: Python

Data Analysis and Manipulation: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn

Notebook Environment: Jupyter Notebook

## Files

1. Travel Price Prediction.ipynb

This notebook includes:

Dataset Information: Detailed description of the dataset used.
Exploratory Data Analysis (EDA): Understanding the dataset, identifying patterns, and visualizing trends.
Feature Engineering: Processes for creating and selecting features that improve the model's predictive performance.
Modeling: Building and training the regression model.
Evaluation: Assessing the model's performance and saving the final model.

2. uber-and-lyft-dataset-boston-ma.csv
This CSV file is the main dataset used in the project, containing various features related to Uber and Lyft trips in Boston.
