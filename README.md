# Airbnb Pricing Analysis

This project analyzes how Airbnb listing prices vary across neighborhoods and what factors drive those differences. It focuses on descriptive analysis using Seattle data from Inside Airbnb.

This project focuses on descriptive analysis rather than causal modeling. The goal is to clearly understand pricing patterns and communicate insights clearly.

This repository contains my individual contribution to a larger group project, including data cleaning and pricing analysis.

---

## Overview

Airbnb listings vary widely in price even within the same city. This analysis focuses on identifying the main factors that explain those differences, including location, property characteristics, and listing features.

---

## My Contribution

- Cleaned and prepared the raw Airbnb dataset
- Identified and handled data issues such as outliers and inconsistent pricing
- Designed and implemented the pricing analysis
- Explored how neighborhood and listing characteristics relate to price

---

## Key Questions

1. How does pricing vary across neighborhoods?
   - Which neighborhoods have the highest average prices
   - How much variation exists within neighborhoods

2. How do property characteristics relate to price?
   - Room type, bedrooms, and accommodates
   - Price per guest as a normalized metric

3. What features are associated with higher prices within neighborhoods?
   - Differences after accounting for size and capacity

---

## Data

Source: Inside Airbnb (Seattle)
[Inside Airbnb Data](https://insideairbnb.com/get-the-data/)

The dataset includes listing level information such as:
- price
- neighborhood
- room type
- bedrooms and accommodates
- amenities and review metrics

Raw data is not included in this repository.

---

## Data Cleaning

Cleaning steps are documented in `01_data_cleaning.ipynb`.

Key decisions:
- Cleaned and converted price and percentage columns from string to numeric
- Removed listings with long minimum stays to avoid monthly pricing bias
- Created price per guest to normalize across listing sizes
- Investigated and handled extreme outliers

---

## Analysis

The main analysis is in `02_pricing_analysis.ipynb`.

Approach:
- Descriptive statistics and grouped summaries
- Price normalization to compare across listings
- Visual comparisons across neighborhoods and property types

---

## Key Insights

- Pricing varies significantly across neighborhoods, with central areas commanding higher prices
- Property size and room type explain a large portion of price variation
- Price per guest provides a more consistent comparison across listings
- Some listings reflect monthly pricing and can distort nightly price analysis

---

## Repository Structure

airbnb-pricing-analysis/
├── README.md
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_pricing_analysis.ipynb
├── images/

---

## Tools

- Python
- pandas
- matplotlib / seaborn

---

