# Air Pollution Analysis Project 🌍

## Overview
This project focuses on analyzing air pollution data using Python.  
The objective was to clean raw environmental data, perform exploratory data analysis (EDA), and generate insights using visualizations.

## Project Goals
- Understand pollution trends over time
- Compare pollution levels across states
- Handle missing and inconsistent data
- Detect and remove outliers
- Build analytics-ready dashboards

## Dataset Features
The dataset contains historical pollution records with columns such as:

- State
- Location
- Date
- SO2
- NO2
- RSPM
- Other environmental indicators

## Tools & Technologies Used
- :contentReference[oaicite:0]{index=0}
- :contentReference[oaicite:1]{index=1}
- :contentReference[oaicite:2]{index=2}
- :contentReference[oaicite:3]{index=3}
- :contentReference[oaicite:4]{index=4}
- :contentReference[oaicite:5]{index=5}

## Data Cleaning Steps
- Removed columns with excessive null values
- Dropped unnecessary columns
- Filled missing numerical values using mean
- Filled categorical values using mode
- Removed outliers using IQR method

## Exploratory Data Analysis
Created visualizations for:

- State-wise pollution records
- Average pollutant comparison
- Yearly pollution trends
- Histogram distribution of pollutants

## Key Insights
- Pollution levels vary significantly by region
- Some states had higher monitoring activity
- RSPM showed major pollution concern
- Time-based analysis revealed changing trends

## Business Use Cases
- Smart city planning
- Public health awareness
- Pollution control strategy
- Government reporting dashboards

## How to Run Project

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook
