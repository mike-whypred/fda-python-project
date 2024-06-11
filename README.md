# Financial Data Analysis with Python

This project focuses on financial data analysis using Python, specifically performing KMeans clustering with FRED MD data and Russell 2000 returns. The analysis is conducted using a Jupyter Notebook (`financial_analysis.ipynb`).

## Project Overview

The main goal of this project is to utilize KMeans clustering to identify patterns and groupings within financial data sourced from the FRED MD database and Russell 2000 index returns. This clustering technique helps in understanding the underlying structures in the data, which can be useful for investment strategies, risk management, and economic research.

## Dataset

### FRED MD Data
FRED MD (Federal Reserve Economic Data - Monthly Database) provides a comprehensive collection of macroeconomic data. It includes various economic indicators such as GDP, unemployment rates, inflation, and more.

### Russell 2000 Returns
The Russell 2000 index measures the performance of the small-cap segment of the US equity market. It includes approximately 2,000 of the smallest securities based on a combination of their market cap and current index membership.

## Features

- Data Collection: Download and preprocess FRED MD data and Russell 2000 returns.
- Data Cleaning: Handle missing values and normalize the data.
- KMeans Clustering: Apply KMeans clustering algorithm to the cleaned data.
- Visualization: Visualize the clustering results to interpret the findings.

## Installation

To run this project, you need to have Python and Jupyter Notebook installed. The required libraries should be prepackaged with Jupyter Notebooks / Anaconda Distribution of Python and Google Colab Notebooks.


## Required Libraries
* pandas
* numpy
* scikit-learn
* matplotlib
* yfinance
* datetime
