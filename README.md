# Sales_Analysis

Overview:

This repository contains Python code for conducting sales analysis using the Pandas and Matplotlib libraries. We explore 12 months' worth of sales data driven from Kaggle, investigating various aspects such as sales trends, product performance, and customer behavior.

Data Cleaning:

In the initial phase, we focus on cleaning the data to ensure its reliability and accuracy for analysis. This includes tasks such as removing NaN values, filtering rows based on specific conditions, and converting column types as necessary.

Data Exploration:

In this section, we delve into several high-level business questions to gain insights into the sales data:

1. Best Month for Sales --> Identifying the month with the highest sales volume and determining the total revenue generated during that period.

2. Top Selling City --> Determining which city recorded the highest number of product sales.

3. Optimal Advertising Time --> Analyzing the data to find the best time slots for displaying advertisements to maximize customer engagement and sales.

4. Frequently Sold Together Products -->Identifying pairs of products that are frequently purchased together by customers.

5. Best Selling Product -->Determining the product with the highest sales volume and investigating the factors contributing to its success.


Methods Used:

To address these questions, we employ various techniques and methods including:

1.Concatenating multiple CSV files to create a consolidated dataset.

2.Adding new columns to the DataFrame for additional insights.

3.Parsing cell values to extract relevant information.

4.Using the .apply() method for custom data transformations.

5.Utilizing groupby operations for aggregate analysis.

6.Visualizing results using bar charts and line graphs.

7.Adding labels and annotations to enhance the interpretability of visualizations.
