# Earthquake Data Analysis

## Overview
This project involves the analysis of the "Significant Earthquakes 1965-2016" dataset. The dataset includes various details about each earthquake, such as date, time, location, magnitude, depth, and more. The primary goal is to clean, transform, and visualize the data to extract meaningful insights.

## Data Cleaning and Transformation
### Task 1: Data Cleaning
- **Date Column Splitting**: The 'Date' column was split into 'Year', 'Month', and 'Day' to facilitate more granular time-based analysis.
- **Removing Columns with High Missing Values**: Columns with more than 50% missing values were removed to maintain data integrity.

### Task 2: Categorization
- **Magnitude Categorization**: The 'Magnitude' field was categorized into three groups: 'Low', 'Moderate', and 'High' using the `pd.cut()` function.

### Task 3: Data Reshaping
- **Pivot Table**: A pivot table was created to summarize the average magnitude of earthquakes by year and magnitude category.
- **Melting Data**: The dataset was reshaped using the `melt()` function to focus on 'Year', 'Month', 'Day', and 'Magnitude'.

### Task 4: Data Visualization
Four different types of graphs were constructed:
1. **Line Chart**: Showing the trend of the average magnitude of earthquakes over the years.
2. **Bar Chart**: Displaying the count of earthquakes by magnitude category.
3. **Scatter Chart**: Illustrating the relationship between the magnitude and depth of the earthquakes.
4. **Histogram**: Providing a view of the frequency distribution of the depths of earthquakes.

### Task 5: Working with Dates
- **Day of the Week Extraction**: Added a new column to represent the day of the week for each earthquake.
- **Annual Earthquake Count**: Used the `resample()` function to calculate the annual count of earthquakes.

## Tools and Libraries
- **Python**: Primary programming language used.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating various types of plots and charts.

## Conclusion
This project demonstrates a comprehensive approach to data analysis, from cleaning and transforming data to visualizing it in various informative ways. Through these processes, we gain valuable insights into the patterns and characteristics of earthquake occurrences over the years.
