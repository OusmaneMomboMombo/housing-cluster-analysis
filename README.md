# Housing Market Analysis

This project explores various machine learning techniques to analyze and segment the housing market using clustering algorithms. The dataset combines two sources: house sales data and mortgage rate information, providing a comprehensive view of the real estate market.


## Table of Contents

- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Files in the Repository](#files-in-the-repository)
- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [Author](#author)


## Introduction

The goal of this project is to apply clustering algorithms (DBSCAN, K-Means, Agglomerative Clustering, and Spectral Clustering) to segment the housing market into meaningful clusters based on property features. This analysis provides actionable insights for real estate stakeholders, such as targeted marketing strategies, pricing optimization, and investment opportunities.

The dataset used in this project is a fusion of two datasets:
1. **kc-house-data.csv**: Contains detailed information about houses, including price, square footage, number of bedrooms, location, and more.  
   Source: [Kaggle - KC House Data](https://www.kaggle.com/datasets/shivachandel/kc-house-data)
2. **MORTGAGE30US.csv**: Provides data on average 30-year mortgage rates in the United States.  
   Source: [Kaggle - 30-Year Conventional Mortgage Rate](https://www.kaggle.com/datasets/federalreserve/30-year-conventional-mortgage-rate)

These datasets were merged using the date as the common key, resulting in the final dataset (`FUSION.csv`).


## Dataset Overview

The final dataset (`FUSION.csv`) consists of **4117 observations** with **22 columns**, including derived features such as:
- **age**: Current year minus the year of construction.
- **sqft_grade_interaction**: Interaction between living space (`sqft_living`) and the grade of the house.

Key features include:
- **House-related features**: Price, bedrooms, bathrooms, square footage, floors, waterfront, view, condition, grade.
- **Location-related features**: Latitude (`lat`), longitude (`long`).
- **Time-related features**: Year built (`yr_built`), year renovated (`yr_renovated`), age.


## Files in the Repository

- **FUSION.csv**: The cleaned and enriched dataset used for analysis.
- **house_market_analysis.ipynb**: Jupyter Notebook containing the complete analysis, including data preprocessing, clustering, and visualization.
- **requirements.txt**: List of Python libraries required to run the project.


## Installation

To set up the project locally, follow these steps in your command prompt ::

1. Clone the repository:

*git clone https://github.com/your-username/housing-market-analysis.git*
*cd housing-market-analysis*

2. Install the required dependencies:

*pip install -r requirements.txt*

3. Launch Jupyter Notebook to explore the analysis:

*jupyter notebook house_market_analysis.ipynb*


## Usage

The Jupyter Notebook (`house_market_analysis.ipynb`) contains step-by-step instructions for:
- Loading and preprocessing the dataset.
- Applying clustering algorithms (DBSCAN, K-Means, Agglomerative Clustering, Spectral Clustering).
- Visualizing and interpreting the results.

You can modify the code or parameters to adapt the analysis to other datasets or specific use cases.


## Contributions

Contributions are welcome! If you have suggestions, bug fixes, or improvements, feel free to open an issue or submit a pull request. Please ensure that your contributions align with the project's goals and maintain the quality of the codebase.


## Author

Ousmane MOMBO MOMBO