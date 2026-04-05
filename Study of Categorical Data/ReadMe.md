
**Experiment-11**

**Name: Prithvi Ratkalkar**

**PRN: 25070123165**

**Batch: ENTC A1**

**Title**

**Study and Implementation of Categorical Data Analysis in Python**

**Aim**

To study and implement various techniques for analyzing categorical data using the Pandas library, including frequency distribution, cross-tabulation, and grouping.

**Objectives**

- To understand the difference between nominal and ordinal categorical data.
- To perform frequency counting and percentage distribution of categories.
- To apply cross-tabulation (Crosstab) to find relationships between two variables.
- To perform data grouping and sorting based on categorical features.
- To filter specific subsets of data from a categorical dataset.

**Theory**

Categorical data represents types of data which may be divided into groups. In Python’s Pandas library, categorical data is handled efficiently to provide insights into patterns and distributions within a dataset.

**1. Frequency Distribution**

Frequency counting is the most basic form of categorical analysis. It involves counting how many times each unique value appears in a column. Normalized frequency provides the percentage distribution, allowing for a better understanding of the proportion of each category within the whole.

**2. Cross-Tabulation (Crosstab)**

Cross-tabulation is used to identify the relationship between two categorical variables. It creates a contingency table that displays the frequency distribution of the variables, such as comparing "Payment Method" across different "Product Categories" or "Gender" across "Grades".

**3. Unique Value Identification**

Identifying unique values is crucial for understanding the diversity of a dataset. The unique() function lists all distinct labels, while nunique() provides the total count of distinct categories.

**Metadata and Exploration**

**Value Counts**:Used to determine the frequency of categories like 'Electronics' or 'Clothing' in an order database, or 'Grades' in a student database.

**Percentage Distribution**: By using normalize=True, the data is transformed into percentages to show that a specific category might represent, for example, 40% of the total data.

**Sorting and Filtering**: Data is sorted alphabetically by category or filtered to isolate specific groups, such as extracting only orders belonging to the 'Electronics' category.

**Advanced Categorical Analysis**

**Crosstab**: This operation is applied to find overlaps, such as determining how many 'New' vs. 'Returning' customers chose 'Express' delivery.

**Grouping (Groupby)**: This allows for multi-level analysis, such as seeing the distribution of grades specifically within each engineering department.

**Applications of Categorical Analysis**

**Market Research**: Analyzing customer preferences across different demographic categories.

**Academic Performance**: Studying the distribution of student grades across different departments.

**Inventory Management**: Tracking the frequency of sales across various product categories.Logistics: Comparing delivery types and payment methods to optimize supply chain efficiency.

**Conclusion**
The experiment demonstrates that categorical data analysis is essential for extracting meaningful patterns from non-numerical data. By using value counts, cross-tabulation, and grouping, we can effectively summarize large datasets and understand the relationships between different variables, such as how student performance (Grade) varies across different departments.

