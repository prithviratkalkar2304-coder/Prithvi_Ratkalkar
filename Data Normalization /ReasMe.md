**Experiment-14**

**Name: Prithvi Ratkalkar**

**PRN: 25070123165**

**Batch: ENTC A1**

**Title**

**Implementation of Data Normalization and Data Type Conversion in Python**

**Aim**

To study and implement data preprocessing techniques, specifically Data Normalization and Data Type Conversion, to standardize numerical scales and ensure consistent data structures using Pandas and NumPy.

**Objectives**
- To understand the importance of Data Normalization in scaling numerical features.
- To implement scaling techniques such as Simple Feature Scaling, Min-Max Scaling, and Z-score Normalization.
- To perform Data Type Conversion to ensure compatibility for mathematical operations.
- To identify and handle inconsistent data types in imported datasets.

**Theory on Data Normalization**

Data Normalization is a crucial preprocessing step used to adjust the values of numeric columns in a dataset to a common scale without distorting differences in the ranges of values. This is essential because many machine learning algorithms perform poorly if the features have vastly different scales (e.g., comparing Age 0–100 with Salary 0–1,000,000).

Normalization Techniques

1. Simple Feature Scaling: Divides each value by the maximum value of that column, resulting in a range between 0 and 1.
Formula: $x_{new} = \frac{x_{old}}{x_{max}}$ 
2. Min-Max Scaling: Rescales the data to a fixed range, usually 0 to 1, by subtracting the minimum and dividing by the range.
Formula: $x_{new} = \frac{x_{old} - x_{min}}{x_{max} - x_{min}}$
3. Z-score Normalization (Standardization): Transforms data to have a mean of 0 and a standard deviation of 1.
Formula: $x_{new} = \frac{x_{old} - \mu}{\sigma}$

**Theory on Data Type Conversion**

Data Type Conversion (or Type Casting) is the process of converting one data type into another to ensure data integrity and computational efficiency. Often, data imported from CSV files may be read as "Object" (string) even if they contain numbers, preventing mathematical analysis.

Common Conversion Tasks
- Object to Float/Int: Converting string-based numbers into actual numerical types to allow for operations like mean() or sum().
- Int to Float: Ensuring precision during division or normalization operations.
- Boolean/Categorical Conversion: Converting text labels into categories to save memory and improve processing speed.

**Data Wrangling Operations**
Based on the implemented code in the notebook, the following wrangling tasks were performed:
1. Scaling Numerical Columns
In the Student Database and Cars93 datasets, columns such as "CGPA", "Marks", and "Price" were normalized. This ensures that high-magnitude values (like Price) do not dominate low-magnitude values (like CGPA) during analysis.
2. Standardizing Data TypesThe dtypes attribute was used to inspect the dataset. The .astype() method was then applied to convert columns that were incorrectly identified as objects into numerical formats, enabling the application of the normalization formulas mentioned above.

**Applications**
- Machine Learning: Preprocessing features for algorithms like K-Nearest Neighbors (KNN) or Support Vector Machines (SVM) that are sensitive to scale.
- Data Integration: Aligning data types from different sources (e.g., SQL databases vs. CSV files) before merging.
- Statistical Analysis: Ensuring all variables are on a comparable scale for calculating correlations or variances.

**Conclusion**

The experiment demonstrates that Normalization and Type Conversion are vital for data quality. Normalization brings all numerical features to a uniform scale, facilitating fair comparison, while Data Type Conversion ensures that the data is in a format suitable for complex mathematical computations. These steps are fundamental to creating a reliable and accurate data analysis pipeline.
