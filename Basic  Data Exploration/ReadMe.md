# Data Exploration with Pandas: 40 Essential Functions

This repository contains a Jupyter Notebook that demonstrates 40 essential functions for basic data exploration and analysis using Python and the pandas library. These functions are particularly useful for anyone working with tabular data, such as CSV or Excel files, and provide a comprehensive overview of the most common operations required for data analysis.

## Overview

The notebook is organized to cover the following key areas of data exploration:

1. **Loading Data**: Functions to read data from various file formats like CSV and Excel.
2. **Inspecting Data**: Functions to understand the structure, types, and completeness of the data.
3. **Data Cleaning**: Functions for handling missing values, duplicates, and data type conversions.
4. **Data Transformation**: Functions to manipulate data frames, including sorting, filtering, grouping, and merging.
5. **Data Summarization**: Functions for descriptive statistics, aggregations, and pivot tables.
6. **Advanced Operations**: Functions for more advanced data manipulation like cross-tabulation, conditional formatting, and memory usage optimization.

## Functions Covered

Below is a categorized list of all 40 functions covered in the notebook:

### Loading Data
- `pd.read_csv()`
- `pd.read_excel()`
- `df.to_csv()`
- `df.to_excel()`

### Inspecting Data
- `df.head()`
- `df.tail()`
- `df.info()`
- `df.describe()`
- `df.shape`
- `df.columns`
- `df.dtypes`
- `df.memory_usage()`

### Data Cleaning
- `df.isnull().sum()`
- `df.dropna()`
- `df.fillna()`
- `df.duplicated()`
- `df.drop_duplicates()`
- `df.replace()`

### Data Transformation
- `df.sort_values()`
- `df.sort_index()`
- `df.rename()`
- `df.set_index()`
- `df.reset_index()`
- `df.groupby()`
- `df.agg()`
- `df.apply()`
- `df.applymap()`

### Data Summarization
- `df.value_counts()`
- `df.corr()`
- `df.cov()`
- `df.pivot_table()`
- `pd.crosstab()`
- `df.quantile()`
- `df.melt()`
- `df.stack()`

### Advanced Operations
- `df.groupby('Region').sum()`
- `df.groupby('Region').agg()`
- `pd.pivot_table()`
- `pd.crosstab()`
- `df.memory_usage(deep=True)`

## How to Use This Notebook

1. **Clone the repository** to your local machine:
    ```bash
    git clone https://github.com/joydeb1729/Data-Analysis.git
    ```
2. **Navigate to the repository directory**:
    ```bash
    cd Data-Analysis
    ```
3. **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook Data_Exploration_with_Pandas.ipynb
    ```

## Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas library

You can install the required libraries using pip:
```bash
pip install pandas jupyter
