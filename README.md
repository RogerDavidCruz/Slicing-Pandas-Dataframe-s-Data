# Guided Lab 386.3.11 – Slicing Pandas DataFrames

## Overview

This lab introduces DataFrame slicing in Pandas using the `.iloc[]` and `.loc[]` indexers. It demonstrates how to extract specific rows, columns, and ranges of data for exploration, cleaning, transformation, and analysis.

## Objectives

* Slice DataFrame rows and columns
* Use `.iloc[]` for position-based selection
* Use `.loc[]` for label-based selection
* Select specific rows, columns, and ranges
* Create smaller DataFrames from larger datasets

## Technologies Used

* Python 3
* Pandas
* Google Colab / Jupyter Notebook

## Methods & Concepts

* `pd.DataFrame()` – Create a DataFrame from Python data
* `.iloc[]` – Select rows and columns by integer position
* `.loc[]` – Select rows and columns by labels
* `df.iloc[row_slice, column_slice]` – Slice data using index positions
* `df.loc[row_labels, column_labels]` – Slice data using row and column labels
* `first_valid_index()` – Identify the first non-missing value in a Series or column

## Key Points

* `.iloc[]` uses integer positions and excludes the ending position
* `.loc[]` uses labels and includes the ending label
* `:` selects all rows or columns in a specified direction
* Slicing can return a single row, selected columns, or a smaller DataFrame

## Topics Covered

* Row slicing with `.iloc[]`
* Column slicing with `.iloc[]`
* Selecting rows and columns together
* Selecting specific columns with `.loc[]`
* Selecting a range of labeled columns
* Understanding inclusive and exclusive slicing
* Creating filtered subsets for analysis

## Dataset

* Sample employee DataFrame
* Sample team performance DataFrame

## Learning Outcome

By completing this lab, I gained hands-on experience slicing Pandas DataFrames by both position and label using `.iloc[]` and `.loc[]`, allowing me to efficiently extract specific subsets of data for further analysis.
