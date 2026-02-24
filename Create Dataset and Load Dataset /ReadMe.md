# Experiment–10

# Creation and Loading of Datasets in Python

---

## Aim

To understand how to create custom datasets using dictionaries, store them as CSV files, and load external datasets for analysis using the Pandas library.

---

## Objectives

- To construct a student dataset using Python dictionaries  
- To save a DataFrame into CSV format for permanent storage  
- To import external CSV files into a Pandas DataFrame  
- To explore dataset metadata and generate basic statistical summaries  
- To retrieve data using coordinate-based selection methods such as `loc` and `iloc`  

---

## Theory

Data analysis workflows generally begin with either creating new data or importing existing data. Python, along with the Pandas library, offers efficient tools for managing both processes.

---

### 1. Creating and Exporting Datasets

Datasets can be manually built using Python dictionaries, where:

- Keys represent column names  
- Values represent lists of corresponding data entries  

After converting the dictionary into a Pandas DataFrame, it can be saved as a CSV file using the `to_csv()` method. This converts the data stored in memory into a permanent file format for future use.

---

### 2. Importing External Datasets

The `read_csv()` function is widely used to load CSV files into a structured DataFrame. It converts raw CSV data into an organized tabular format, making it easy to analyze large datasets such as the Cars93 dataset without manual data entry.

---

## Data Exploration Techniques

Pandas provides several tools for understanding dataset structure:

- **info()**  
  Displays a concise summary including column names, non-null counts, and data types.

- **shape**  
  Returns a tuple indicating the number of rows and columns.

- **head() / tail()**  
  Shows the first or last five rows to quickly inspect data.

- **dtypes**  
  Lists the data type of each column (e.g., `int64`, `float64`, `object`).

---

## Data Retrieval Methods

- **Label-Based Indexing (`loc`)**  
  Accesses rows and columns using their labels or names.

- **Integer-Based Indexing (`iloc`)**  
  Retrieves data using numerical positions (row and column indices), which is helpful when labels are unknown.

---

## Statistical Analysis

Basic descriptive statistics help summarize datasets:

- **Mean** – The average value of numerical data  
- **Median** – The middle value in an ordered dataset  
- **Mode** – The most frequently occurring value  

These measures help understand both numerical and categorical distributions.

---

## Applications of Dataset Management

- **Data Migration**  
  Converting dictionary-based data into structured files for centralized storage.

- **Automated Reporting**  
  Importing regularly updated CSV files to generate business reports.

- **Large-Scale Analysis**  
  Working with extensive datasets, such as automotive performance records, for research and comparison.

- **Data Validation**  
  Using `info()` and `shape` to detect missing values or inconsistencies in uploaded datasets.

---

## Conclusion

This experiment demonstrates the complete lifecycle of dataset management in Python. By creating a custom `student_database.csv` file and importing `Cars93.csv`, we practiced both data generation and data ingestion. Applying statistical calculations (mean, median, mode) along with retrieval techniques (`loc`, `iloc`) ensures that datasets are not only stored efficiently but are also ready for meaningful analysis.
