# 📉 Customer Churn Analysis

An end-to-end exploratory data analysis (EDA) project investigating customer churn. This project utilizes Python, Pandas, Plotly, and Seaborn to identify key drivers of cancellations, subscription tenures, and customer retention metrics.

## 🚀 Project Overview
This repository contains a comprehensive Jupyter Notebook (`customer_churn_analysis.ipynb`) that analyzes a dataset of customer subscriptions. The primary goal of this project is to understand why customers cancel their subscriptions, how long they stay before leaving, and what factors most influence their decisions.

### Key Features
- **SQL Database Integration:** Connecting to a local SQLite database (`customer_churn.db`) and using SQL queries to extract, filter, and load raw customer data directly into Pandas DataFrames.
- **Data Preparation:** Processing dates, handling missing values, and engineering new features like `tenure_days` to track customer lifetimes.
- **Exploratory Data Analysis (EDA):** Discovering trends and patterns across different customer segments (demographics, subscription plans, contract types).
- **Correlation Analysis:** Identifying statistical relationships between variables like Monthly Charges, CLTV (Customer Lifetime Value), and Churn Risk.

## 📊 Visualizations and Insights

Here are all the key visual insights derived from the dataset:

### 1. Tenure Days Distribution by Churn
Understanding how customer lifespan relates to cancellation rates.
![Tenure Days Distribution](tenure%20days%20distribution%20by%20churn.png)

### 2. Customer Lifetime Value (CLTV) by Churn Status
Analyzing if higher-value customers are less likely to churn.
![CLTV by Churn Status](cltv%20by%20churn%20status.png)

### 3. Contract Type vs Churn Risk
How different contract structures impact the likelihood of a customer leaving.
![Contract Type vs Churn Risk](contract%20type%20vs%20churn%20risk.png)

### 4. Churn Rate by Plan
Which subscription plans have the highest retention?
![Churn Rate by Plan](churn%20rate%20by%20plan.png)

### 5. Churn Rate by Country
Geographical breakdown of customer retention.
![Churn Rate by Country](churn%20rate%20by%20country.png)

### 6. Proportion of Cancellation Reasons
What customers explicitly cite when leaving the service.
![Proportion of Cancellation](proportion%20of%20cancellation.png)

### 7. Overarching Churn Trend
Time-series view of cancellation spikes and trends.
![Churn Trend](churn%20trend.png)

### 8. Correlation Heatmap
Statistical correlation matrix across all numerical variables.
![Correlation Heatmap](corelation%20heatmap.png)

### 9. Additional Heatmap 1
Detailed numerical correlation view.
![Heatmap 1](heatmap%201.png)

### 10. Additional Heatmap 2
Further detailed numerical correlation view.
![Heatmap 2](heat%20map%202.png)

### 11. Seaborn Axis Grid
Multi-variable distribution and relationships.
![Seaborn Axis Grid](seaborn%20axix%20grid.png)

### 12. Seaborn Axis Grid 2
Secondary multi-variable distribution analysis.
![Seaborn Axis Grid 2](seaborn%20axix%20grid%202.png)


## 🛠️ Technologies Used
- **Python** (Data processing)
- **Pandas** (Data manipulation)
- **SQLite3 & SQL** (Database connection and data extraction)
- **Plotly Express & Seaborn** (Interactive and statistical graphing)
- **Jupyter Notebook** (Analysis environment)

## 💻 Setup and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Akshay-Notfound/customer-churn-analysis.git
   ```
2. Ensure you have the required libraries installed: `pip install pandas plotly seaborn jupyter`
3. Open `customer_churn_analysis.ipynb` in your Jupyter environment.
4. Run all cells to view the data analysis and interactive charts.
