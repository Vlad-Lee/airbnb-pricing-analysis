# Airbnb Seattle Pricing Analysis

## Overview
This project analyzes Airbnb listing prices in Seattle using public data from Inside Airbnb. The goal is to understand how prices vary across neighborhoods and what listing characteristics help explain those differences.

This repository contains my individual contribution to a larger group project. I was responsible for data cleaning and the analysis of neighborhood level pricing patterns.

## Research Question
How do Airbnb prices vary across Seattle neighborhoods, and what listing characteristics help explain those differences?

## My Contribution
- Cleaned and prepared the dataset for analysis
- Handled missing price data by backfilling from prior quarter data where available
- Trimmed extreme outliers to reduce skew
- Filtered to comparable short-term listings
- Conducted analysis of price variation across neighborhood groups
- Interpreted spatial pricing patterns and their relationship to listing characteristics

## Data
This project uses data from Inside Airbnb, a publicly available dataset of Airbnb listings.

Seattle listings can be downloaded here:
https://insideairbnb.com/get-the-data/

The raw data is not included in this repository due to file size constraints. To reproduce the analysis, download the Seattle listings dataset (listings.csv.gz) and place it in the `data/` folder.

## Methods
The analysis includes:
- cleaning and converting price data
- backfilling missing values
- trimming outliers
- grouping neighborhoods into predefined clusters
- comparing median prices across neighborhoods
- analyzing listing size and room type patterns

## Key Findings
- Prices vary substantially across Seattle neighborhood groups
- The highest priced areas are concentrated in central Seattle, near downtown and major commercial hubs
- Larger listings and room type composition help explain part of the price differences
- Median price is more reliable than average due to skew

## Tools
- Python
- pandas
- matplotlib
- Jupyter Notebook

## Limitations
This is a descriptive analysis, not a causal model. The results show pricing patterns but do not establish causality.

## Author
Vlad Lee
