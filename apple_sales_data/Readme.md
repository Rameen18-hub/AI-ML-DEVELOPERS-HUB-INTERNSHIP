

# Apple Sales Data Analysis (2024)

This project involves analyzing a dataset containing Apple product sales and revenue data across various regions and states for the year 2024. The dataset includes information on iPhone, iPad, Mac, Wearables sales, and Services Revenue.

## Features

- Loading and inspecting the dataset
- Renaming columns for clarity
- Data cleaning and null value checks
- Descriptive statistics and summary
- Data aggregation and grouping
- Data slicing and filtering
- Data visualization with pie charts, bar charts, histograms, and more

## Dataset Overview

- Total records: 1000
- Columns:
  - `State`
  - `Region`
  - `iPhone Sales (in million units)`
  - `iPad Sales (in million units)`
  - `Mac Sales (in million units)`
  - `Wearables (in million units)`
  - `Services Revenue (in billion $)`

## Data Operations

- Loaded data from `apple_sales_2024.csv`
- Renamed the `Country` column to `State`
- Checked for null values and confirmed data completeness
- Described data with statistical summaries
- Grouped data by `State` and `Region` for detailed insights
- Sliced data for specific subsets
- Used value counts for categorical analysis
- Visualized data distributions and proportions using pie, bar, histogram, density, and line plots

## Usage

1. Ensure you have `pandas` and `matplotlib` installed:
```bash
pip install pandas matplotlib
```

2. Load and analyze your dataset:
```python
import pandas as pd
df = pd.read_csv("apple_sales_2024.csv")
# Perform operations as shown in the script
```

3. Visualize data:
```python
df['Region'].value_counts().plot(kind="pie")
```
