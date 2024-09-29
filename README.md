# Page View Time Series Visualizer

This project visualizes time series data of daily page views on the freeCodeCamp.org forum from May 9, 2016, to December 3, 2019. The visualizations include a line chart, bar chart, and box plots, which provide insights into the page view trends over time, seasonality, and yearly growth.

## Overview

The **Page View Time Series Visualizer** project helps analyze patterns in the page views on the freeCodeCamp.org forum. It creates three main types of visualizations:
1. **Line Plot**: A plot of daily page views over time.
2. **Bar Plot**: A bar chart showing the average monthly page views per year.
3. **Box Plots**: Two box plots showing the distribution of page views by year and month.

The project uses **Pandas**, **Matplotlib**, and **Seaborn** for data manipulation and visualization.

## Project Structure

- `time_series_visualizer.py`: Contains the main functions to generate the plots (line, bar, and box).
- `main.py`: Used for running the project and testing functions locally.
- `test_module.py`: Contains unit tests for the project functions.
- `fcc-forum-pageviews.csv`: The dataset containing the daily page views (make sure to provide this file).
- `README.md`: This file, explaining the project setup and usage.

## Visualizations

### Line Plot

The **line plot** shows the total page views on the forum from May 2016 to December 2019. This helps identify long-term trends in the data, such as increases or decreases in traffic.

- **Title**: Daily freeCodeCamp Forum Page Views (5/2016 - 12/2019)
- **X-axis**: Date
- **Y-axis**: Page Views

### Bar Plot

The **bar plot** displays the average daily page views per month, grouped by year. This chart highlights any seasonal changes in traffic and helps track overall growth across the years.

- **X-axis**: Years
- **Y-axis**: Average Page Views
- **Legend**: Months

### Box Plots

There are two **box plots**:
- **Year-wise Box Plot**: Shows how the distribution of page views has changed over the years, giving insights into variations or trends.
- **Month-wise Box Plot**: Shows how page views fluctuate across different months, helping identify seasonal trends.


