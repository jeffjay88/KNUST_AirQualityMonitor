# KNUST_AirQualityMonitor
Python script for air quality data analysis


# Air Quality Monitoring Data Visualization
This repository contains code for visualizing air quality monitoring data using Python, Pandas, and Matplotlib. The code allows you to read data from CSV files, perform data wrangling and quality checks, and generate informative visualizations.

# Prerequisites
Before running the code, make sure you have the following installed:

# Python (version 3.7 or higher)
Pandas library
Matplotlib library

# Usage
<ol>
<li> Ensure that the CSV data files are located in the Data directory, and the header file (header.txt) is located in the Data directory as well.</li>
<li> Open the code in a Python environment or IDE of your choice.</li>
<li> Modify the code as needed:</li>
<ul>
<li>Adjust the quantities and units lists to match the air quality parameters you have in your data.</li>
<li>Customize the plot settings, such as plot size, color schemes, and axis labels, based on your preferences.</li>
</ul>
<li>Run the code to generate the visualizations.</li>
</ol>

# Code Overview
The code consists of the following main components:

1. Data Wrangling & Quality Check:

    - The read_data function reads the CSV files and performs data wrangling tasks such as combining the data, setting the column names, converting dates to a datetime format, and handling missing values.
    - The read_data function requires the file paths of the CSV files and the header file as input parameters.
2. Visualization:

    - The code generates visualizations using Matplotlib. It creates subplots to display multiple air quality parameters over time.
    - The visualization includes line plots of the raw data, rolling averages, and hourly means for each parameter.
    - The second set of visualizations includes a heatmap-like representation of each parameter, showing the variations across days and hours.
 
# Contributing
Contributions to the code are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

# License
Feel free to use and modify the code as per your needs.

# Acknowledgments
This code was developed as part of an air quality monitoring project. We would like to acknowledge the contributions of all project team members and the support received.
