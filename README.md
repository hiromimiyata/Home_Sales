# Home_Sales

## Introduction
This repository contains the code and data for the Home Sales assignment. The goal of this assignment is to analyze and process a dataset containing information about home sales and generate insights from it. The data is stored in CSV format and is transformed into Parquet format for more efficient querying and analysis.

## Dataset
The dataset used in this assignment contains the following columns:

sale_id: A unique identifier for each home sale.
sale_date: The date of the home sale.
sale_price: The price at which the home was sold.
bedrooms: The number of bedrooms in the home.
bathrooms: The number of bathrooms in the home.
sqft_living: The total square footage of the living space in the home.
sqft_lot: The total square footage of the lot on which the home is built.
floors: The number of floors in the home.
waterfront: A binary indicator (0 or 1) representing whether the home is located on the waterfront.
view: A rating (0-4) representing the view from the home.
condition: A rating (1-5) representing the overall condition of the home.
grade: A rating (1-13) representing the overall grade given to the home based on various factors.
sqft_above: The square footage of the home above ground level.
sqft_basement: The square footage of the basement in the home.
yr_built: The year the home was built.
yr_renovated: The year the home was last renovated (0 if not renovated).
zipcode: The ZIP code of the location of the home.
lat: The latitude coordinate of the location of the home.
long: The longitude coordinate of the location of the home.
sqft_living15: The square footage of the living space of the nearest 15 neighboring homes.
sqft_lot15: The square footage of the lot of the nearest 15 neighboring homes.
Technologies Used
The assignment is implemented using the following technologies:

Apache Spark: The data processing and analysis are performed using Apache Spark, which provides a distributed computing framework for big data processing.
Python: The code is written in Python programming language, and PySpark is used to interact with Apache Spark.
Google Colab: The development environment used for this assignment is Google Colab, which provides free access to GPU and TPU for running notebooks.
Code Files
Home_Sales_starter_code_colab.ipynb: This Jupyter Notebook contains the Python code for data loading, cleaning, transformation, and analysis. It is structured in sequential steps to perform the necessary tasks.

## Instructions
To run the code in the notebook:

Upload the CSV file containing the home sales data to the Google Colab environment.
Execute the code cells in the notebook sequentially, following the step-by-step instructions.
The notebook will read the CSV data, perform data cleaning and transformation, and write the processed data to Parquet format for more efficient querying.
Analyze the data to generate insights and answer any specified questions or tasks.
Note: Make sure to set up Google Drive integration and provide the correct path to read and write data to/from Google Drive if required.

## Conclusion
The Home Sales assignment demonstrates how to use Apache Spark with Python to process and analyze a dataset of home sales. The code performs data cleaning, transformation, and analysis to generate insights from the data. By converting the data to Parquet format, we improve data storage and query performance for large-scale data processing.
