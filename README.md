📌 Overview
This project is a Python-based script designed to generate and visualize synthetic (fake) COVID-19 data. It is primarily built for educational purposes, demonstrating how to use Python libraries for data generation, manipulation, and data visualization.

Using the Faker library alongside random generation, the script creates a mock dataset spanning the last two years across multiple countries and plots the data using standard Python visualization tools.

🚀 Features
Synthetic Data Generation: Automatically generates 500 records of mock COVID-19 data including dates, countries, confirmed cases, deaths, recovered cases, and active cases.

Data Processing: Utilizes pandas to structure, clean, and aggregate the generated data.

Comprehensive Visualizations: * Time Series Trend: A Matplotlib line chart tracking confirmed cases over time.

Bar Chart: A Seaborn bar plot showing the top countries by total confirmed cases.

Pie Chart: A Matplotlib pie chart illustrating the distribution of cases across countries.

Scatter Plot: A Seaborn scatter plot mapping the relationship between confirmed cases and deaths.

Correlation Heatmap: A Seaborn heatmap displaying the correlation matrix of numerical metrics (Confirmed, Deaths, Recovered, Active).

Interactive Time Series: A Plotly Express interactive line graph for tracking the overall COVID-19 trend.
