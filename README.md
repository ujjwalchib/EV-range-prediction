# Electric Vehicle Range Prediction - Regression Analysis

## Overview

This project focuses on predicting the range of electric vehicles (EVs) using regression analysis. The Jupyter notebook includes steps such as data preprocessing, exploratory data analysis (EDA), model training, and evaluation of multiple regression models.

## Table of Contents

- [Overview](#overview)
- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)

## Introduction

Electric vehicle (EV) range prediction is crucial for advancing the development and adoption of EVs. Accurate range prediction helps alleviate range anxiety among users and improves overall EV efficiency. This project employs various regression techniques to predict the range based on several vehicle features.

## Dataset

The dataset includes the following features:

- `Battery Capacity (kWh)`: The capacity of the vehicle's battery.
- `Vehicle Weight (kg)`: The weight of the vehicle.
- `Motor Power (kW)`: The power output of the vehicle's motor.
- `Aerodynamics (Cd)`: The drag coefficient of the vehicle.
- `Tire Resistance`: The resistance of the vehicle's tires.
- `Range (km)`: The range the vehicle can travel on a full charge (target variable).

The dataset has been cleaned and preprocessed to handle missing values, normalize numerical features, and encode categorical variables.

## Requirements

Ensure you have the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Installation

1. Clone the repository:

```bash
git clone https://github.com/sarthaknimbalkar/EV-range-prediction.git
```

2. Navigate to the project directory:

```bash
cd electric-vehicle-range-prediction
```

## Project Structure

```bash
electric-vehicle-range-prediction/
├── data/
│   └── dataset.csv
├── notebooks/
│   └── Electric Vehicle Range Prediction - Regression Analysis.ipynb
├── README.md
└── LICENSE
```

## Usage

1. Open the Jupyter notebook:

```bash
jupyter notebook "notebooks/Electric Vehicle Range Prediction - Regression Analysis.ipynb"
```

2. Follow the steps in the notebook to preprocess the data, explore the data, train regression models, and evaluate their performance.

## Exploratory Data Analysis (EDA)

In the EDA section, we:

- Visualize the distribution of each feature.
- Analyze correlations between features.
- Identify outliers and handle them appropriately.
- Visualize the relationship between features and the target variable (range).

## Modeling

In the modeling section, we:

- Split the data into training and testing sets.
- Train multiple regression models, including:
  - Linear Regression
  - Decision Tree Regression
  - Random Forest Regression
  - Gradient Boosting Regression
  - Support Vector Regression (SVR)
- Evaluate model performance using metrics such as RMSE, MAE, and R^2 score.
- Perform hyperparameter tuning to improve model performance.

## Results

The results section includes:

- Comparative analysis of different regression models.
- Visualization of model performance metrics.
- Discussion of the best-performing model and its implications.

## Future Work

Potential future improvements include:

- Incorporating additional features to improve prediction accuracy.
- Using more advanced regression techniques.
- Implementing real-time range prediction in an EV management system.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
