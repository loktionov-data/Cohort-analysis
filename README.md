# Cohort-analysis

## Overview
This project performs **Cohort Analysis** on the **ecommerce_customer dataset** using Python. Cohort analysis is a powerful method to analyze customer behavior over time. In this analysis, customers are grouped by their first purchase month in **2023**, and additional segmentation is performed by **age** and **gender**. This provides insights into customer spending trends and patterns across different demographics.

## Key Features
1. **Dataset**
   - Contains customer transaction data, including:
     - Customer ID
     - Purchase date
     - Product category
     - Product price
     - Quantity
     - Total Purchase Amount
     - Payment Method
     - Customer Age
     - Returns
     - Customer Name
     - Gender
     - 	Churn
2. **Cohort Analysis**
   - Calculated the total sum spent by each cohort on a monthly basis.
   - Segmented spending data by **age groups** and **gender** to identify key trends.
3. **Visualization**:
   - Monthly total spending for each cohort as a heatmap.
   - Spending trends for **age groups** and **gender groups** visualized separately by month.

---

## Technologies Used
- **Python** for data manipulation, analysis, and visualization.
- **Jupyter Notebook** for organizing analysis.
- **Libraries**:
  - `pandas` for data wrangling and cohort calculations.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for visualizations.
