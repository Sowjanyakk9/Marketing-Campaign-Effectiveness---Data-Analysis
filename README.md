Project Overview
This project analyzes the effectiveness of marketing campaigns by exploring customer data from various countries. Using interactive data visualizations, the goal is to understand the impact of customer demographics, income, education, and marital status on marketing campaign success. Key insights will help businesses refine their marketing strategies and target specific customer segments more effectively.

Key Steps
Data Cleaning:
Cleaned the dataset by addressing missing values in the Income column.
Fixed country names for accurate geographical representation in visualizations.
Data Transformation:
Normalized the Income column to a range of $0 - $100K for consistency in analysis.
Added a country mapping to handle inconsistent country codes and provide meaningful labels.
Exploratory Data Analysis (EDA):
Analyzed customer demographics, including income distribution, education level, and marital status.
Investigated the relationship between income and campaign success.
Visualizations:
Income Distribution (Histogram): Displays income distribution of customers, scaled between 0 and 100K.
Education Distribution: Bar plot showing the distribution of customers' education levels.
Marital Status Distribution: Bar plot displaying the distribution of customers' marital status.
Customer Map (Choropleth): A map showing customer distribution by country, with color-coded income scales.
Key Metrics:
Total Customers: Displays the total number of customers based on country selection.
Avg. Scaled Income: Displays the average income of customers (scaled between 0 and 100K).
Most Common Education: Displays the most common education level of customers.
Most Common Marital Status: Displays the most common marital status of customers.
Dashboard:
An interactive dashboard built with Dash and Plotly allows users to filter customer data by country.
Dynamically updates key performance indicators (KPIs) and visualizations based on selected country.
Insights
Income: Understanding the income distribution helps identify potential target segments for campaigns.
Education: Customers with higher education levels may respond differently to campaigns.
Marital Status: Marital status may correlate with purchasing behavior, influencing marketing strategies.
Geographic Insights: The choropleth map helps identify which countries have higher engagement, assisting in region-specific marketing efforts.

Access the dashboard in your browser at:
http://127.0.0.1:8053/
Accessing the Dashboard:
Use the dropdown to filter data by country.
View the updated KPIs and visualizations in real-time based on the selection.
Conclusion
This project provides valuable insights into the effectiveness of marketing campaigns by analyzing customer demographics and income data. The interactive dashboard enables businesses to refine their marketing strategies and target the most relevant customer segments.

