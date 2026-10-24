# Walmart Sales Dashboard using Power BI

## Introduction

This project serves as an improvement towards becoming an actual Data Analyst. Using Power BI to make the dashboard, showcasing skills recruiters look for.

The project focuses on analyzing Walmart's historical sales data using Power BI to explore sales performance, store rankings, weekly sales trends, and the relationship between sales and economic indicators. The dashboard provides an interactive overview of key sales metrics, allowing users to filter results by year and store, and investigate patterns across different aspects of the business.

Check the Power BI Dashboard file here —> [Walmart Sales Dashboard.pbix file](/Walmart%20Sales%20Dashboard.pbix)

## Background

Retail sales can be influenced by economic conditions, and understanding this helps businesses evaluate performance and identify patterns that supports in better decision-making.

The goal of this project is for the improvement of my Data Analytics career by transforming raw data into meaningful visualizations, further understanding how patterns work, and improving my Power BI skills overall.

The dataset used in this project came from [Kaggle's Datasets](https://www.kaggle.com/datasets/9592bb3b3c89493fabab56b4317ae10dbd70e6b66d2d464fb7f08c6a5903556d/data).


## Dashboard Overview

![Dashboard](/images/Walmart_Sales_Dashboard_Page1.png)
This dashboard displays the cleaned up historical sales data of Walmart, highlighting trends, comparisons, top-N, and overall sales performance.

## Analysis

### 1. Overall Sales Performance

The dataset contains approximately **$6.74 billion** in total recorded sales, with an average weekly sales value of approximately **$1.05 million** per store-week record across **45** stores. These KPIs provide a high-level overview of sales performance during the period covered by the dataset.

### 2. Store Performance

The **top 10** store visualization ranks stores according to their total recorded sales. **Store 20 leads** the displayed ranking, followed by **Stores 4 and 14**. This comparison helps identify high-performing stores and provides a starting point for investigating differences in sales performance across locations.

### 3. Weekly Sales Trends

The weekly sales trend shows recurring fluctuations and several noticeable peaks throughout the observed period. These patterns can be explored further to investigate seasonal behavior, holiday periods, and changes in sales over time.

### 4. Holiday Sales Analysis

The holiday visualization compares holiday and non-holiday records. It provides a starting point for examining whether holiday periods are associated with different sales performance. A comparison of average weekly sales for the two groups is needed to determine the size and direction of any difference.

### 5. CPI Trends

The CPI line chart shows an overall upward trend during the period displayed. This provides context for exploring how changes in consumer price levels coincide with Walmart's sales performance. An upward CPI trend alone does not establish its effect on sales.

### 6. Unemployment Rate vs. Sales

The scatter plot explores the relationship between unemployment rates and weekly sales. The observations are widely distributed, suggesting that the relationship should be examined carefully rather than assuming a simple linear pattern. Further analysis, such as calculating correlation and comparing stores separately, could help clarify the relationship.

### 7. Temperature vs. Sales

The temperature scatter plot examines whether weekly sales vary across different temperature levels. The observations are concentrated in certain temperature ranges, with substantial variation in sales at similar temperatures. This suggests that temperature alone may not explain differences in weekly sales.

## Tools I Used

- **Power BI:** Used to make the visualizations I needed to make it into a working dashboard.

- **Visual Studio Code:** Used to make this README file and prepare files for pushing to a remote repository.

- **Git:** Used for version control to track changes and manage the project during development.

- **GitHub:** Used to store and document the project.

## Skills Showcased

- **Power BI:** Dashboard development, report design, and interactive visualizations.

- **Data Cleaning and Transformation:** Preparing data, correcting data types, and formatting numerical values appropriately.

- **Power Query:** Cleaning up and transforming raw values into their proper formats before actually uploading into Power BI 

- **DAX:** Creating explicit measures, calculated columns, and dimensional tables for sales metrics, descriptive category labels, and useable table for more in-depth analysis respectively.

- **Star Schema:** By making fact and dim tables, avoiding to use flat tables, for a more complex usage of data.

- **Data Visualization:** Designing KPI cards, bar charts, donut charts, line charts, and scatter plots.

- **Interactive Reporting:** Implementing slicers to filter data by year and store.

- **Exploratory Data Analysis (EDA):** Examining sales trends, comparing store performance, and exploring relationships between sales and economic indicators.

- **Business Intelligence:** Presenting key metrics and data patterns in a consolidated dashboard.

## What I Learned

I have applied all of my Power BI learnings into an actual dataset, make the dashboard from scratch. This strengthens my Power BI skills even more, making me more eligible for Data Analyst job roles.

The key concepts I applied includes:
- Proper usage of visualizations on certain problems to solve, such as `KPIs`, `Donut Charts`, `Line Charts`, `Bar Charts`, and `Scatter Plots`.
- Making `explicit measures` for `aggregations` that are usable in multiple visuals.
- Using `DAX` in making the `date_dim` table for the `star schema` and necessary `measures`.
- Using `Power Query` to clean and transform column values before loading to have better formats, cleaner columns, and for the `star schema` with the help of `DAX`.
- How to implement slicers to make dashboard analysis more flexible and allow users to examine specific years and stores.
- How to explore relationships between weekly sales and external factors such as unemployment rates, temperature, and CPI without assuming that correlation implies causation.
- How to improve dashboard readability through consistent colors, appropriate number formatting, clear chart titles, and an organized layout.
- How to communicate data patterns through visualizations that support further business analysis.

## Conclusion

This project strengthened my Power BI skills by combining data preparation, Power Query, DAX, data visualization, and exploratory analysis in a single interactive dashboard. It provided an opportunity to examine Walmart's sales performance across multiple stores and time periods while exploring how holidays and economic indicators relate to weekly sales.

Through this project, I gained practical experience in turning raw data into an organized business intelligence report. The dashboard demonstrates my ability to prepare data, build interactive visualizations, and investigate business questions using Power BI.