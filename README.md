# Cohort Analysis of User Retention

This project presents a cohort analysis focused on user retention over time. It is an improved version of an earlier project, enhanced with clearer visualizations, additional metrics, and better structured code for clarity and interpretability.

> ⚠️ This project is an improved version of a previously published cohort analysis. The visuals and analysis have been refined to better demonstrate retention behavior and interpret results effectively.

---

## Overview

The goal of this analysis is to understand how user retention varies depending on when users first joined (the cohort), and how well different cohorts are retained over time.

Key steps in this project:
1. **Data Cleaning & Preparation**
   - Parsing dates and standardizing formats.
   - Removing anomalies and duplicates.
2. **Cohort Labelling**
   - Assigning users to cohorts based on their first purchase month.
3. **Retention Matrix Creation**
   - Calculating monthly retention rates for each cohort.
4. **Visualizations**
   - Line chart showing retention across months for each cohort.
   - Bar plot showing 1-month retention rate by cohort.

## Visualizations

### Retention Line Chart
A line plot showing how retention changes over time for each of the cohorts. Helps identify trends and differences in user behavior.

### 1-Month Retention Bar Plot
A bar chart showing the percentage of users retained after the first month, by cohort. This helps compare initial stickiness between different user groups.

## Insights
- Earlier cohorts tend to show slightly better retention, possibly due to lower competition or stronger onboarding.
- Some cohorts show sharp drop-off after the first month, highlighting a potential need for better user engagement early in the lifecycle.

## Technologies Used
- **Python** (data analysis)
- **Pandas** (data manipulation)
- **Matplotlib** & **Seaborn** (visualization)
- **Jupyter Notebook** (documentation and analysis)

## Dataset
The dataset is a synthetic transactional dataset, where each row represents a user's purchase activity, including user ID and purchase date.

---


