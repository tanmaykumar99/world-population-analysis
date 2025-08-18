# World Population Analysis

---

## Overview

This project explores historical world population data, providing insights into trends across countries and continents. It generates correlation matrices, line plots, and box plots to identify patterns, outliers, and growth trends.

## Features

- Data cleaning and exploratory analysis
- Null value and uniqueness checks
- Correlation heatmaps
- Continent-wise population aggregation
- Transposed plots for time series visualization
- Boxplots for detecting outliers

---

## Requirements

Install the required Python packages:
```bash
pip install pandas seaborn matplotlib

You also need:

- Python 3.7

## How to Run

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Word Population Pandas Analysis.ipynb"
   ```
2. Run all cells to fetch and visualize data.

## Example Output
The notebook generates plots showing population data analysis and correlations.

![Pandas Dataframe](images/df.png)

![Dataframe Info](images/df_info.png)

![Dataframe Description](images/df_describe.png)

![Total Nulls](images/nulls_in_df.png)

![Unique Values](images/unique_values.png)

![Top 5 Countries by Population](images/top_5_pop.png)

![Bottom 5 Countries by Population](images/least_5_pop.png)

![Correlation Matrix](images/correlation_matrix.png)

![Correlation Heatmap](images/correlation_heatmap.png)

![Oceania Countries](images/Oceania_countries.png)

![Population vis by Continents](images/pop_by_continent.png)

![Population vis by Decade](images/pop_by_decade.png)

![Outliers Vis](images/visualizing_outliers.png)