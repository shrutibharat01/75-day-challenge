# Pandas Exploration - 75-Day Data Science Challenge

Welcome to Day 12 of my 75-Day Data Science Challenge! Today, we're diving deep into the Pandas library, a powerful tool for data manipulation and analysis in Python. This README provides an overview of essential Pandas functionalities and concepts.

## Table of Contents

1. [Pandas Series](#pandas-series)
2. [Series Indexing & Slicing](#series-indexing--slicing)
3. [Series with Python Functionality](#series-with-python-functionality)
4. [Series Attributes and Functions](#series-attributes-and-functions)
5. [Pandas DataFrame](#pandas-dataframe)
6. [DataFrame Attributes and Functions](#dataframe-attributes-and-functions)
7. [Aggregation Method](#aggregation-method)
8. [Groupby Method](#groupby-method)
9. [Merging](#merging)
10. [Multi-Index Series and DataFrame](#multi-index-series-and-dataframe)
11. [Stacking and Unstacking](#stacking-and-unstacking)
12. [Long vs Wide Data (Melt and Pivot)](#long-vs-wide-data-melt-and-pivot)
13. [Vectorized String Operations](#vectorized-string-operations)
14. [Datetime Objects](#datetime-objects)
15. [Resampling, Shifting](#resampling-shifting)
16. [Rolling Window (Smoothing)](#rolling-window-smoothing)

## Pandas Series

A Series is a one-dimensional array-like object that can hold any data type. It's similar to a column in a DataFrame.

## Series Indexing & Slicing

Indexing and slicing in Series allow for easy access and manipulation of data. Use `loc[]` for label-based indexing and `iloc[]` for position-based indexing.

## Series with Python Functionality

Pandas Series support Python functionalities like membership operators, loops, and relational operators.

## Series Attributes and Functions

Series have various attributes and functions such as `size`, `dtype`, `index`, `values`, `astype`, `drop_duplicates`, `isnull`, `dropna`, `fillna`, `isin`, `apply`, `count`, `describe`, `duplicated`, `name`, `is_unique`, `nunique`, `rank`, `hasnans`, `between`, `clip`, `head`, `tail`, `sample`, `value_counts`, `sort_values`, and `sort_index`.

## Pandas DataFrame

A DataFrame is a two-dimensional, size-mutable, and potentially heterogeneous tabular data structure with labeled axes (rows and columns).

## DataFrame Attributes and Functions

DataFrames have attributes and functions like `shape`, `info`, `rename`, `set_index`, `reset_index`, `iloc`, `loc`, `sort_index`, `mean`, `mode`, `max`, `min`, and `sum`.

## Aggregation Method

Aggregation functions allow for data summarization. You can pass a dictionary or list to the `agg` method to apply multiple aggregation functions.

## Groupby Method

The `groupby` method groups data based on specified columns and allows for aggregate functions to be applied. Attributes include `get_group`, `groups`, and `agg`.

## Merging

The `merge` method combines DataFrames based on a common column, similar to SQL joins. The `concat` method can be used for both vertical and horizontal concatenation.

## Multi-Index Series and DataFrame

Multi-Index allows for hierarchical indexing, providing a way to work with higher-dimensional data. Functions include `from_tuples`, `from_product`, `transpose`, and `swaplevel`.

## Stacking and Unstacking

Stacking transforms columns into rows and unstacking pivots rows into columns, allowing for data reshaping.

## Long vs Wide Data (Melt and Pivot)

The `melt` function transforms wide data into long format, and the `pivot` function transforms long data back into wide format.

## Vectorized String Operations

Pandas provides vectorized string operations, which enable efficient string manipulation using functions like `str.contains` and `str.capitalize`.

## Datetime Objects

Pandas supports datetime objects like `Timestamp`, `DatetimeIndex`, `to_datetime`, and `date_range`, facilitating date and time manipulations.

## Resampling, Shifting

Resampling changes the frequency of time-series data, and shifting moves data up or down along the time axis.

## Rolling Window (Smoothing)

The rolling window method applies a function over a sliding window of data, which is useful for calculating moving averages and smoothing data.

Thank you for reading! I’d love to hear your thoughts or questions about this blog on Pandas. Feel free to join the conversation in the comments below!

Let’s continue the discussion on other platforms too. Connect with me on LinkedIn or Github for more data science insights and discussions. If you found this blog helpful, consider sharing it with your network!

Github: [shrutibharat01](https://github.com/shrutibharat01)

LinkedIn: [shrutibhrarat0105](https://www.linkedin.com/in/shrutibharat0105/)
