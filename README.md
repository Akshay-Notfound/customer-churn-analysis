# Customer Churn Analysis

An exploratory data analysis (EDA) project investigating customer churn. Features interactive Plotly visualizations to identify key drivers of cancellations and retention metrics.

## Project Overview
This repository contains a Jupyter Notebook (`churn_analysis.ipynb`) that analyzes a dataset of customer subscriptions. The goal of this project is to understand why customers cancel their subscriptions, how long they stay before leaving, and what factors most influence their decisions.

## Key Features
- **Data Preparation:** Processing dates, handling missing values, and creating new features like `tenure_days` to track customer lifetimes.
- **Exploratory Data Analysis (EDA):** Discovering trends and patterns across different customer segments (demographics, subscription plans, etc.).
- **Interactive Visualizations:** Using Plotly Express to create dynamic, interactive charts (like histograms of tenure days split by churn status) to clearly communicate findings.

## Technologies Used
- **Python** (Data processing)
- **Pandas** (Data manipulation)
- **Plotly Express** (Interactive graphing)
- **Jupyter Notebook** (Analysis environment)

## Setup and Usage
1. Clone the repository.
2. Ensure you have the required libraries installed: `pip install pandas plotly jupyter`
3. Open `churn_analysis.ipynb` in your Jupyter environment.
4. Run all cells to view the data analysis and interactive charts.
