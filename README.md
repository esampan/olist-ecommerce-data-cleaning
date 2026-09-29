# Olist E-Commerce Data Cleaning

## Project Overview

This project focuses on cleaning and validating data from the Olist Brazilian e-commerce dataset, using Python and Pandas in Google Colab.
The dataset, originally available through Kaggle, contains information from an online marketplace, including customers, sellers, products, orders, order items, and payments. The datasets vary in size, with several containing more than 90,000 records and some exceeding 100,000 records.

The goal of this project is to prepare the data for future analysis by identifying data quality issues, standardizing relevant fields, and validating the structure and consistency of each dataset.

## Tools Used

* Python
* Pandas
* Google Colab
* GitHub
* Datasets Cleaned

The project includes data cleaning and validation for the following Olist datasets:

1. Customers
2. Orders
3. Order Items
4. Order Payments
5. Order Reviews
6. Products
7. Sellers

Each dataset was examined and validated through a series of data quality checks, including:

* Checking dataset shape and size
* Inspecting column names and data types
* Checking for missing values
* Checking for duplicate rows
* Checking for duplicate IDs
* Cleaning and standardizing relevant fields
* Converting date columns to appropriate datetime formats
* Checking categorical and unique values
* Validating relationships and data consistency where applicable
* Performing final validation after cleaning

## Notebook

The complete data cleaning process and validation results are available in the Jupyter Notebook:

[olist(ecommerce)_data_cleaning.ipynb](https://github.com/esampan/olist-ecommerce-data-cleaning/blob/cb2a05003f1c053f135662e7a934e744fb744212/olist(ecommerce)_data_cleaning.ipynb)

The notebook includes the Python code, intermediate outputs, tables, and validation results from the cleaning process.

## Dataset

The project uses the Olist Brazilian e-commerce dataset, a collection of datasets describing transactions and marketplace activity from an online e-commerce platform in Brazil.

The data includes information about:

* Customers — customer identifiers, locations, and geographic information
* Sellers — seller identifiers and locations
* Products — product information and categories
* Orders — order status and purchase, delivery, and estimated delivery dates
* Order Items — products included in each order, sellers, prices, and shipping information
* Order Payments — payment methods, installments, and payment values
* Product Categories — Portuguese product category names and their English translations

The datasets contain tens of thousands to more than 100,000 records, providing a realistic dataset for practicing data cleaning and validation on relatively large e-commerce data.

## Project Status

Data cleaning and initial validation completed.

The cleaned datasets are now structured and validated for use in future data analysis and visualization projects.
