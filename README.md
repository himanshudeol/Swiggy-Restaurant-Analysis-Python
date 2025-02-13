# Swiggy Restaurant Data Analysis using Python

This repository contains a data analysis project on the Swiggy restaurant dataset using python. The analysis explores various aspects of restaurants listed on Swiggy, including price distribution, rating patterns, delivery time analysis, and cuisine preferences. Visualizations and insights are provided to understand the Indian restaurant landscape.  Key libraries used include Pandas, NumPy, Matplotlib, and Seaborn.

## Introduction

Swiggy is a popular online food delivery platform in India. This project aims to analyze a dataset of restaurants listed on Swiggy to gain insights into the restaurant industry. The analysis covers various aspects, from pricing and ratings to delivery times and cuisine preferences.

## Dataset

The dataset used in this project is a third-party collection of restaurant data from Swiggy. It contains information about restaurants across several Indian cities, including:

- Restaurant ID
- Area
- City
- Restaurant Name
- Price (average cost for two)
- Average Rating
- Total Ratings
- Food Type (cuisine)
- Address
- Delivery Time

## Project Overview

The project follows a typical data analysis workflow:

1. **Data Loading and Cleaning:** The dataset is loaded using Pandas. Basic data cleaning steps are performed (if necessary), such as handling missing values or duplicates (although this particular dataset was fairly clean).
2. **Exploratory Data Analysis (EDA):**  EDA is performed to understand the data's characteristics. This includes calculating descriptive statistics, visualizing distributions, and exploring relationships between variables.
3. **Data Visualization:** Matplotlib and Seaborn are used to create visualizations, including histograms, bar charts, box plots, and scatter plots.
4. **Insight Generation:**  The analysis aims to answer questions like:
    - What are the most common cuisines?
    - How do prices vary across different cities and cuisines?
    - Is there a correlation between price and ratings?
    - What is the distribution of delivery times?
    - Which cities have the highest/lowest average restaurant prices and ratings?
5. **Correlation Analysis:** A correlation analysis is conducted to determine the relationship between restaurant prices and average ratings.
6. **Delivery Time Analysis:** Outliers in delivery time are identified and discussed.
7. **City-wise Analysis:** Average price and rating per city are calculated and visualized.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
