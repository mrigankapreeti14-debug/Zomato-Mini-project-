# Zomato-Mini-project-
Zomato Restaurant Exploration and EDA using Python, Pandas, Matplotlib, and Seaborn, covering data cleaning, restaurant pricing, and rating analysis.
# Zomato Restaurant Exploration

## Project Overview

**Zomato Restaurant Exploration** is a mini data analysis project focused on exploring restaurant data using **Python, Pandas, Matplotlib, and Seaborn**. The project performs basic **Exploratory Data Analysis (EDA)** to understand restaurant pricing, ratings, and data quality.

The dataset is loaded into a Pandas DataFrame and examined to understand its structure, missing values, duplicate records, and important restaurant-related attributes.

## Objectives

The main objectives of this project are:

* To explore and understand the Zomato restaurant dataset.
* To inspect the size and structure of the dataset.
* To identify and handle missing values.
* To detect and remove duplicate records.
* To analyze restaurant price ranges.
* To compare restaurant ratings across different price ranges.
* To visualize important patterns and trends in the data.

## Technologies Used

* **Python**
* **Pandas** – for data loading, cleaning, and analysis
* **Matplotlib** – for data visualization
* **Seaborn** – for creating statistical plots
* **Google Colab / Jupyter Notebook** – for executing the analysis

## Data Cleaning

The project includes several data-cleaning steps:

1. Checking the dataset shape using `df.shape`.
2. Examining column information using `df.info()`.
3. Checking for missing values using `df.isnull().sum()`.
4. Identifying duplicate records using `df.duplicated().sum()`.
5. Removing duplicate records using `drop_duplicates()`.
6. Filling missing values in the **Cuisines** column with `"Unknown"`.
7. Filling missing values in **Average Cost for two** using the median value.
8. Converting the **Aggregate rating** column into a numerical rating field.

## Data Visualization

Two major visualizations are created:

### 1. Restaurants by Price Range

A **count plot** is used to determine which price range contains the largest number of restaurants.

### 2. Ratings by Price Range

A **bar plot** is used to compare the average restaurant ratings across different price ranges.

These visualizations make it easier to identify relationships between restaurant pricing and customer ratings.

## Conclusion

This mini project demonstrates the basic workflow of an **Exploratory Data Analysis project**, including data loading, inspection, cleaning, and visualization. By analyzing price ranges and restaurant ratings, the project provides a simple understanding of patterns within the Zomato restaurant dataset.

The project can be further extended by analyzing **popular cuisines, restaurant locations, online delivery availability, table booking, votes, cost distribution, and relationships between ratings and other restaurant features**.
