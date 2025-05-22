# Page View Time Series Visualizer

This project analyzes page view data from the freeCodeCamp forum and creates visualizations to identify trends, seasonal patterns, and distributions over time. Built as part of the freeCodeCamp Data Analysis with Python certification.

## Overview

The dataset contains daily page views between May 2016 and December 2019. This project includes:
- A **line plot** to show daily page view trends
- A **bar plot** to show average monthly page views for each year
- Two **box plots** to show the distribution of page views by year and by month

## Features

- Data cleaning: removal of outliers (2.5th and 97.5th percentiles)
- Time series processing using pandas
- Visualizations created with `matplotlib` and `seaborn`

## Skills Demonstrated

- Data preprocessing with pandas
- Date/time indexing and grouping
- Statistical plotting with seaborn
- Function structuring and modular coding

## Files Included

- `page_view_time_series_visualizer.py`: Main script
- `fcc-forum-pageviews.csv`: Source dataset
- `line_plot.png`: Line chart output
- `bar_plot.png`: Bar chart output
- `box_plot.png`: Box plot output

## How to Run

1. Install the required libraries:
```bash
pip install pandas matplotlib seaborn
```

2. Run the script:
```bash
python page_view_time_series_visualizer.py
```

3. View the output images:
- `line_plot.png`
- `bar_plot.png`
- `box_plot.png`

## Dataset Source

Provided by [freeCodeCamp](https://www.freecodecamp.org/), originally from their Data Analysis with Python certification project.

---

Created by Carlos Ortiz
