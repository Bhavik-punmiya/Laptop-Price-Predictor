# Laptop Price Estimator

This project aims to predict the prices of laptops using machine learning techniques. The dataset required extensive cleaning and feature engineering due to variations in column values.

## Streamlit Application 
![image](https://github.com/Bhavik-punmiya/Laptop-Price-Predictor/assets/118907757/94529618-73d6-42a2-a319-0f0c2657f42f)



## Project Overview

The dataset consists of information about various laptops, including their specifications and prices. Each entry contains details such as brand, type, screen size, processor, RAM, storage, graphics card, operating system, weight, and price.

## Data Cleaning and Feature Engineering

The dataset underwent significant cleaning and feature engineering to handle inconsistencies and prepare it for modeling. This process involved standardizing values, handling missing data, and transforming features to improve predictive performance.

## Dataset Overview

The following table provides an overview of the dataset:

| ID | Brand | Type | Screen Size (inches) | Display | Processor | RAM | Storage | Graphics Card | Operating System | Weight (kg) | Price (USD) |
|----|-------|------|-----------------------|---------|-----------|-----|---------|----------------|------------------|--------------|-------------|
| 11 | HP    | Notebook | 15.6                  | Full HD 1920x1080 | Intel Core i3 6006U 2GHz | 4GB | 500GB HDD | Intel HD Graphics 520 | No OS | 1.86 | 18381.0672 |
| 12 | Apple | Ultrabook | 15.4                 | IPS Panel Retina Display 2880x1800 | Intel Core i7 2.8GHz | 16GB | 256GB SSD | AMD Radeon Pro 555 | macOS | 1.83 | 130001.6016 |
| 13 | Dell  | Notebook | 15.6                 | Full HD 1920x1080 | Intel Core i3 6006U 2GHz | 4GB | 256GB SSD | AMD Radeon R5 M430 | Windows 10 | 2.2 | 26581.392 |

## Machine Learning Models

Multiple machine learning models were experimented with to predict laptop prices, including:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Support Vector Machines (SVM)
- Random Forest
- Decision Trees Regressor
- KNeighborsRegressor
- Adaboost
- XGBoost
- Gradient Boost
- Extra Tree
- Voting Classifiers with different models
- Stacking method with different models

## Best Performing Model

After evaluating various models, the Random Forest algorithm yielded the best results in predicting laptop prices.

## Streamlit Application

The project includes a Streamlit application deployed at [Laptop Price Estimator](https://laptop-price-estimator-amzn.streamlit.app/). Users can interact with the application to estimate laptop prices based on their specifications.


## Repository Contents

- **Dataset**: Contains the cleaned dataset used for training and evaluation.
- **Notebooks**: Jupyter notebooks detailing the data cleaning, feature engineering, and model training processes.
- **Models**: Includes trained models for predicting laptop prices. `pipe.pkl` utilizes the Random Forest algorithm for predictions.

## Usage

To replicate the project or explore further:
1. Clone this repository.
2. Install the necessary dependencies specified in `requirements.txt`.
3. Explore the notebooks to understand the data preprocessing and modeling steps.
4. Utilize the provided models for predicting laptop prices.
5. Interact with the Streamlit application for estimating laptop prices based on custom specifications.

