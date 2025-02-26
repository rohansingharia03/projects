# Online Retail Sales Data Analysis

This project aims to analyze and gain insights from an online retail dataset to understand customer behavior, retention strategies, and segmentation. Using Python and libraries such as Pandas, the data was cleaned, and exploratory data analysis (EDA) was performed. Additionally, RFM (Recency, Frequency, and Monetary) segmentation and churn analysis were conducted to derive actionable insights for customer retention.

## Project Overview

This project focuses on the analysis of sales data from an online retail store. It includes several key steps:
1. **Data Cleaning**: Handling missing values, duplicates, and inconsistent formats using Pandas.
2. **Exploratory Data Analysis (EDA)**: Identifying patterns, trends, and relationships in the data to understand customer behavior and sales performance.
3. **RFM Segmentation**: Segmenting customers based on their Recency, Frequency, and Monetary value to identify high-value customers and potential churn risks.
4. **Churn Analysis**: Analyzing customer churn to understand why customers may be leaving and how to retain them.

## Technologies Used

- **Python**: Main programming language for the analysis.
- **Pandas**: Used for data manipulation and cleaning.
- **Matplotlib/Seaborn**: Libraries for data visualization during EDA.
- **Scikit-learn**: For building the churn analysis model.
- **Google Colab**: For interactive data analysis and experimentation.

## Steps Involved

### 1. Data Cleaning
- Removed rows with missing or inconsistent values.
- Filtered out canceled or returned orders.
- Ensured proper date and time formatting.
  
### 2. Exploratory Data Analysis (EDA)
- Analyzed key statistics of the sales dataset such as total sales, order frequency, and revenue trends.
- Visualized customer purchasing behavior using various plots (e.g., bar charts, histograms, box plots).

### 3. RFM Segmentation
- **Recency**: How recently a customer made a purchase.
- **Frequency**: How often a customer makes a purchase.
- **Monetary**: How much money a customer has spent.
- Segmented customers into different groups based on these three metrics to identify high-value customers and potential churn risks.

### 4. Churn Analysis
- Analyzed customer behavior to predict churn using historical data.
- Used features such as the number of orders, total spend, and recency of the last order to predict customer retention.

