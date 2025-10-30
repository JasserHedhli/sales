# Sales Forecasting with LSTM and MLflow

## Overview
This project forecasts sales using a Long Short-Term Memory (LSTM) model.

## Table of Contents
1. [Connecting to the Data Warehouse](#1-connecting-to-the-data-warehouse)
2. [Data Cleaning and Analysis](#2-data-cleaning-and-analysis)
3. [Analysis Conducted](#3-analysis-conducted)
4. [Building the LSTM Model](#4-building-the-lstm-model)
5. [Experiment Tracking with MLflow](#5-experiment-tracking-with-mlflow)
6. [Installation](#6-installation)
7. [Usage](#7-usage)
8. [License](#8-license)

## 1. Connecting to the Data Warehouse
- Connect to the SQL Server using SQL Server Management Studio (SSMS).
- Retrieve data from the fact table using Jupyter Notebook.

## 2. Data Cleaning and Analysis
- Cleaned the data by handling missing values and converting date columns to datetime format.
- Performed exploratory data analysis (EDA) to understand trends.

## 3. Analysis Conducted
- Conducted descriptive statistics and visualized sales trends over time.
- Analyzed correlations between different features and identified seasonal patterns.

## 4. Building the LSTM Model
- Prepared the data for LSTM input by normalizing and creating sequences.
- Built and trained the LSTM model using the prepared dataset.

## 5. Experiment Tracking with MLflow
- Set up MLflow to track parameters, metrics, and the model.
- Logged training parameters and the final model for reproducibility.

## 6. Installation
- Install the necessary dependencies including pandas, pyodbc, scikit-learn, matplotlib, keras, tensorflow, and mlflow.

## 7. Usage
1. Clone the repository.
2. Install the dependencies.
3. Configure the database connection in the Jupyter Notebook.
4. Run the notebook cells sequentially.

## 8. License
This project is licensed under the MIT License.
