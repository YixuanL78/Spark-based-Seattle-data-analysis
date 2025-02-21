# Project Title: Seattle Crime Analysis
##Description:
This project focuses on analyzing crime data in Seattle to identify patterns, trends, and insights that can help local law enforcement and policymakers make informed decisions. The analysis includes:

Crime Categories: Counting the number of crimes for different categories to understand which types of crimes are most prevalent.

District-wise Crime Distribution: Identifying the districts with the highest crime rates and analyzing crime trends in these areas.

Temporal Analysis: Examining crime trends over time, including monthly and hourly distributions, to identify peak crime periods.

Business Impact: Providing insights into how crime trends can impact local businesses and suggesting strategies for resource allocation and preventive measures.

The project uses PySpark for data processing and analysis, and the data is sourced from the Seattle Police Department's public crime dataset.

##Key Insights:
Crime Categories: The most common crimes are related to property (e.g., theft, burglary), followed by crimes against persons (e.g., assault) and society-related crimes (e.g., drug offenses).

High-Crime Districts: The top three districts with the highest crime rates are Downtown Commercial, Capitol Hill, and Northgate.

Temporal Trends: Crime rates peak during the summer months (May-August) and during specific hours of the day (e.g., property crimes peak in the afternoon, while crimes against persons peak in the evening).

Business Impact: The analysis suggests that businesses in high-crime areas should consider increasing security measures during peak crime hours, and local law enforcement should adjust patrol schedules to match crime trends.

##Technologies Used:
PySpark: For data processing and analysis.

Databricks: For running the notebook and visualizing results.

Python Libraries: Pandas, NumPy, Seaborn, and Matplotlib for additional data manipulation and visualization.

##How to Run the Project:
Data Preparation: The dataset is downloaded from the Seattle Police Department's public data portal and loaded into the Databricks environment.

Analysis: The notebook contains code for grouping, filtering, and analyzing the data. Each section of the notebook corresponds to a specific analysis (e.g., crime categories, district-wise crime distribution, temporal analysis).

Visualization: Results are displayed using Databricks' built-in visualization tools, and insights are provided in markdown cells.
