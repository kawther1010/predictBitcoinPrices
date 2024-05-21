# Bitcoin Historical Data Analysis

This project involves analyzing Bitcoin historical data using linear regression to predict the weighted price of Bitcoin based on various features.

## Project Overview

The main objective of this project is to build a linear regression model that can accurately predict the weighted price of Bitcoin using historical data. The dataset used for this project contains Bitcoin price data from January 2012 to March 2021.

## Dataset

The dataset used in this project is the "bitstampUSD_1-min_data_2012-01-01_to_2021-03-31.csv" file, which contains the following columns:
- `Timestamp`: Unix timestamp
- `Open`: Opening price
- `High`: Highest price
- `Low`: Lowest price
- `Close`: Closing price
- `Volume_(BTC)`: Volume of Bitcoin traded
- `Volume_(Currency)`: Volume of currency traded
- `Weighted_Price`: Weighted price of Bitcoin

## Project Structure

- `README.md`: Project overview and instructions.
- `linearregression.ipynb`: Jupyter notebook containing the data analysis and model building code.

## Requirements

The following Python libraries are required to run the code:
- `pandas`
- `scikit-learn`
- `matplotlib`
- `numpy`

You can install these libraries using the following command:
```bash
pip install pandas scikit-learn matplotlib numpy
