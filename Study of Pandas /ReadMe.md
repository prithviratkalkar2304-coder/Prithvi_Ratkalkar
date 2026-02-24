# Experiment–9

# Implementation and Study of Pandas Library in Python

---

## Aim

To explore and implement the Pandas library in Python for effective data manipulation, cleaning, and analysis using Series and DataFrame structures.

---

## Objectives

- To understand the primary data structures: `Series` and `DataFrame`  
- To perform fundamental operations such as data creation, access, and modification  
- To apply data manipulation techniques including adding and removing columns  
- To conduct basic statistical analysis and conditional data filtering  
- To examine dataset properties using attributes like shape, size, and dimensions  

---

## Theory

Pandas is an open-source Python library designed for efficient and intuitive handling of structured or labeled data. Built on top of NumPy, it has become a standard tool for data preprocessing and analysis in the Python ecosystem.

It provides high-performance, flexible data structures that simplify working with relational datasets.

---

## Core Data Structures

- **Series**  
  A one-dimensional labeled array that can store various data types such as integers, floats, or strings.

- **DataFrame**  
  A two-dimensional, size-adjustable, and potentially heterogeneous tabular structure. It consists of multiple Series objects aligned along a shared index.

---

## Important Metadata Attributes

Pandas offers several attributes to inspect dataset structure and properties:

- **Shape**  
  Returns a tuple representing the number of rows and columns (e.g., `(3, 2)`).

- **ndim (Dimensions)**  
  Indicates the number of axes. A Series is 1D, while a DataFrame is 2D.

- **Size**  
  Represents the total number of elements in the dataset (rows × columns).

- **Columns**  
  Displays column labels, which are essential for selecting and manipulating specific data.

---

## Data Operations

### 1. Modifying and Updating Data

DataFrames are mutable, allowing changes after creation:

- **Accessing and Updating Data**  
  Values can be accessed and modified using label-based indexing with `.loc[]`, which selects rows and columns by their labels.

- **Adding Columns**  
  New columns can be created by assigning a list or Series to a new column name.

- **Dropping Columns**  
  The `drop()` method removes unwanted columns.  
  - `axis=1` specifies column removal  
  - `inplace=True` updates the original DataFrame directly  

---

### 2. Filtering Data

Filtering selects specific rows based on logical conditions, commonly known as Boolean indexing:

- **Conditional Selection**  
  Using comparison operators (e.g., `> 99`) generates a Boolean mask that filters rows meeting the condition.

- **Practical Usage**  
  Helpful for identifying specific records, such as high-performing students or detecting outliers.

---

### 3. Statistical Analysis

Pandas provides efficient built-in statistical functions that operate on entire columns without explicit loops.  

Common methods include:

- `mean()`  
- `max()`  
- `min()`  

These functions quickly summarize numerical data and reveal trends.

---

## Applications of Pandas

- **Data Cleaning**  
  Managing missing values (NaN) and correcting inconsistent data types.

- **Financial Analysis**  
  Evaluating trends in stock prices and financial records.

- **Machine Learning Preprocessing**  
  Organizing and transforming raw data before feeding it into models.

- **Database Processing**  
  Handling and analyzing records retrieved from SQL databases.

---

## Conclusion

Pandas is a powerful library for managing and analyzing structured datasets using Series and DataFrame objects. Metadata attributes such as shape and size help verify dataset integrity, while flexible data modification and filtering tools enable precise data handling. Its built-in statistical capabilities make it significantly more efficient than traditional Python data structures for analytical tasks.
