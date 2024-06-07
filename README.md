# World-Climate-Data-Analysis

This project leverages advanced methods to analyze historical climate data and uncover hidden patterns, helping us understand and predict future climate conditions.

## Table of Contents
- [Data Files](#DataFiles)
- [Notebooks](#Notebooks)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## DataFiles

### data_analysis_world.csv
This file contains yearly average temperature, temperature difference with respect to previous year for all countries of the world.

| Column Name    | Description                           |
|----------------|---------------------------------------|
| Year           | Year                                  |
| TAVG           | Average Temperature of the country    |
| Diff           | Temp difference from previous year    |
| Country        | Country     |

### Country.xlsx
This file includes details all countries and how data is collected.

## Notebooks

### Data preprocessing.ipynb
This notebook performs exploratory data analysis (EDA) on the climate data. It includes:
- Main Function of this notebook is to fill missing values
- Summary statistics of the data
- Identification of key trends and insights

### Data analysis.ipynb
This notebook is used for Data Aggregation and analysis on the dataset. It includes:
- Data preprocessing steps
- Data transformation
- Generate data_analysis_world.csv

### Analysis.ipynb
This notebook demonstrates how to use the SARIMA models to make predictions on data. It covers:
- **Exploratory Data Analysis:** The notebook conducts thorough exploratory data analysis, visualizing temperature trends for various cities and identifying seasonal patterns.
- **Modeling with SARIMA:** It demonstrates the application of SARIMA (Seasonal Autoregressive Integrated Moving Average) models for forecasting temperature data, utilizing both historical observations and seasonal components.
- **Evaluation and Comparison:** The notebook evaluates model performance through metrics such as root mean squared error (RMSE), comparing the SARIMA predictions against baseline methods, showcasing the efficacy of the modeling approach.

### Pipeline.ipynb
- **Automated Data Processing:** The pipeline automates the processing of temperature data stored in multiple CSV files within specified directories, including data cleaning, visualization, and analysis, streamlining the workflow for large datasets.

- **Model Training and Evaluation:** It trains SARIMA models on historical temperature data, performs walk-forward validation, and evaluates model performance using root mean squared error (RMSE), providing insights into the effectiveness of forecasting techniques.

- **Persistence and Deployment:** The pipeline saves trained models as pickle files for future use, enabling easy deployment in production environments for real-time temperature forecasting applications.

## Installation
1. Clone the repo:
   ```sh
   git clone https://github.com/vinaysai99/World-Climate-Data-Analysis.git

## Usage
Provide examples of how to use the project. For example:

1. **Using Python Notebooks:**

   To interact with the project using Python notebooks, follow these steps:

   - Ensure you have Jupyter Notebook installed. If not, you can install it via pip:
     ```sh
     pip install notebook
     ```

   - Navigate to the directory containing the project's notebooks:
     ```sh
     cd notebooks/
     ```

   - Start Jupyter Notebook:
     ```sh
     jupyter notebook
     ```

   - This will open a new browser window where you can navigate to the desired notebook (e.g., `data_analysis.ipynb`, `pipeline.ipynb`, etc.).

   - Follow the instructions within the notebook to execute code cells, visualize data, and interact with the project's functionalities.

   - Run all necessary cells to complete the tasks outlined in the notebook.

   - Feel free to modify and experiment with the code to suit your needs.
  
# Contributing

First off, thanks for taking the time to contribute!

The following is a set of guidelines for contributing to the Project.

## How Can I Contribute?

### Reporting Bugs

### Suggesting Enhancements


