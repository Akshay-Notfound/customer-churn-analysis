<div align="center">
  
# 📉 Customer Churn Analysis
### Automated Data Analysis & Business Intelligence

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](#)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](#)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](#)
[![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](#)
[![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](#)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](#)
[![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)](#)

[Notebook](customer_churn_analysis.ipynb) • [Dataset](exported_churn_data.csv) • [Visualizations](#-visualizations-and-insights)

---

</div>

## 🚀 Project Overview
This repository contains a comprehensive Jupyter Notebook (`customer_churn_analysis.ipynb`) that analyzes a dataset of customer subscriptions. The primary goal of this project is to understand why customers cancel their subscriptions, how long they stay before leaving, and what factors most influence their decisions.

### ✨ Key Features
- **SQL Database Integration:** Connecting to a local SQLite database (`customer_churn.db`) and using SQL queries to extract, filter, and load raw customer data directly into Pandas DataFrames.
- **Data Preparation:** Processing dates, handling missing values, and engineering new features like `tenure_days` to track customer lifetimes.
- **Exploratory Data Analysis (EDA):** Discovering trends and patterns across different customer segments (demographics, subscription plans, contract types).
- **Correlation Analysis:** Identifying statistical relationships between variables like Monthly Charges, CLTV (Customer Lifetime Value), and Churn Risk.

## 📊 Visualizations and Insights

Here are all the key visual insights derived from the dataset:

### 1. Tenure Days Distribution by Churn
Understanding how customer lifespan relates to cancellation rates.

<div align="center">
  <img src="tenure%20days%20distribution%20by%20churn.png" alt="Tenure Days Distribution" width="800"/>
</div>

### 2. Customer Lifetime Value (CLTV) by Churn Status
Analyzing if higher-value customers are less likely to churn.

<div align="center">
  <img src="cltv%20by%20churn%20status.png" alt="CLTV by Churn Status" width="800"/>
</div>

### 3. Contract Type vs Churn Risk
How different contract structures impact the likelihood of a customer leaving.

<div align="center">
  <img src="contract%20type%20vs%20churn%20risk.png" alt="Contract Type vs Churn Risk" width="800"/>
</div>

### 4. Churn Rate by Plan
Which subscription plans have the highest retention?

<div align="center">
  <img src="churn%20rate%20by%20plan.png" alt="Churn Rate by Plan" width="800"/>
</div>

### 5. Churn Rate by Country
Geographical breakdown of customer retention.

<div align="center">
  <img src="churn%20rate%20by%20country.png" alt="Churn Rate by Country" width="800"/>
</div>

### 6. Proportion of Cancellation Reasons
What customers explicitly cite when leaving the service.

<div align="center">
  <img src="proportion%20of%20cancellation.png" alt="Proportion of Cancellation" width="800"/>
</div>

### 7. Overarching Churn Trend
Time-series view of cancellation spikes and trends.

<div align="center">
  <img src="churn%20trend.png" alt="Churn Trend" width="800"/>
</div>

### 8. Correlation Heatmap
Statistical correlation matrix across all numerical variables.

<div align="center">
  <img src="corelation%20heatmap.png" alt="Correlation Heatmap" width="800"/>
</div>

### 9. Additional Heatmap 1
Detailed numerical correlation view.

<div align="center">
  <img src="heatmap%201.png" alt="Heatmap 1" width="800"/>
</div>

### 10. Additional Heatmap 2
Further detailed numerical correlation view.

<div align="center">
  <img src="heat%20map%202.png" alt="Heatmap 2" width="800"/>
</div>

### 11. Seaborn Axis Grid
Multi-variable distribution and relationships.

<div align="center">
  <img src="seaborn%20axix%20grid.png" alt="Seaborn Axis Grid" width="800"/>
</div>

### 12. Seaborn Axis Grid 2
Secondary multi-variable distribution analysis.

<div align="center">
  <img src="seaborn%20axix%20grid%202.png" alt="Seaborn Axis Grid 2" width="800"/>
</div>

## 💻 Setup and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Akshay-Notfound/customer-churn-analysis.git
   ```
2. Ensure you have the required libraries installed: `pip install pandas plotly seaborn jupyter`
3. Open `customer_churn_analysis.ipynb` in your Jupyter environment.
4. Run all cells to view the data analysis and interactive charts.
