# Energy Trading Insights: Data Analysis of Singapore's Wholesale Electricity Market

## Introduction

This project analyses the Uniform Singapore Energy Price (USEP) in Singapore's National Electricity Market (NEM). It focuses on constructing analytical models to estimate USEP prices based on merit order and demand data, which is crucial for optimising bidding strategies for market participants, including Battery Energy Storage Systems (BESS).

## Features

- Data cleaning and preprocessing of merit order and demand datasets
- Construction of a merit order curve
- Calculation of market clearing prices
- Unit testing of market clearing price function
- Comparison of calculated prices with actual market prices
- Visualisation of merit order and price dynamics

## Technologies Used

- Python
- Polars for data manipulation
- DuckDB for efficient data processing
- Matplotlib and Seaborn for data visualisation
- Pytest and ipytest for unit testing

## Installation

To run this notebook, you need to install the following libraries:
```bash
pip install polars seaborn matplotlib duckdb pytest ipytest
```
You can do this before you run the notebook, or you can simply run each cell in the notebook.

## Usage
1. clone the repo
   ```
   git clone https://github.com/romanwolf-git/energy_trading_insights.git
   ```
2. Run the notebook cells sequentially to perform data cleaning, analysis, and visualisation.

## Key Components

1. **Data Cleaning**: Standardises column names, creates a datetime index, and handles missing data and outliers.

2. **Merit Order Plotting**: Visualises the merit order curve for specific time periods, showing how supply intersects with demand to determine market clearing prices.

3. **Clearing Price Calculation**: Implements a function to calculate the final clearing price based on demand input.

4. **Price Comparison**: Compares calculated clearing prices with actual market prices.

5. **SQL Implementation**: Includes SQL queries for data analysis (not detailed in the provided excerpt).


## Contributors

[Roman Wolf](https://www.linkedin.com/in/roman-wolf/)