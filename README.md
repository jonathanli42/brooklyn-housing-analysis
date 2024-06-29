# NYC Housing Sales Analysis Using Regression

This repository contains an end-to-end data science project focused on analyzing NYC housing sales data from 2012 to 2023. The project includes data collection, preprocessing, exploratory data analysis, and modeling using linear regression techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Collection and Preprocessing](#data-collection-and-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project aims to analyze and model housing sales prices in NYC, identifying trends and patterns, and building predictive models to estimate house prices based on various features.

## Data Source
The data used in this project is obtained from the NYC Department of Finance: [NYC Property Sales Data](https://www.nyc.gov/site/finance/property/property-annualized-sales-update.page)

## Data Collection and Preprocessing
The `1_data_collection_preprocessing.ipynb` notebook includes:
- Combining housing datasets from 2012 to 2023.
- Cleaning the data, handling missing values, and adding new features.

## Exploratory Data Analysis (EDA)
The `2_exploratory_data_analysis.ipynb` notebook includes:
- Visualizations of housing sales data.
- Analysis of sales distribution by neighborhood and other features.

## Modeling and Evaluation
The `3_modeling_evaluation.ipynb` notebook includes:
- Building and evaluating linear regression, ridge regression, and lasso regression models.
- Hyperparameter tuning using GridSearchCV.
- Pipeline creation for streamlined model training and evaluation.

## Installation
To run the notebooks, ensure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

## Usage
git clone https://github.com/yourusername/nyc-housing-sales-analysis.git
cd nyc-housing-sales-analysis

## Run Jupyter Notebook:
jupyter notebook

## License
This project is licensed under the MIT License.
