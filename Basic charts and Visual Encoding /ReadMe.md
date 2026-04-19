
**Experiment 16**


**Title**

**Basic Charts and Visual Encoding**

**Aim**

To study and implement fundamental data visualization techniques in Python using the Matplotlib and Seaborn libraries, and to understand how to effectively encode and present data through various chart types including line charts, bar charts, histograms, and scatter plots.

**Objectives**

•	To understand the importance of data visualization in data analysis.

•	To implement line charts to visualize trends over time.

•	To create bar charts for comparing categorical data.

•	To construct histograms for understanding data distribution.

•	To generate scatter plots to examine relationships between variables.

•	To use Seaborn for enhanced, aesthetically improved visualizations.

**Theory on Data Visualization**

Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data. Python provides powerful libraries — Matplotlib and Seaborn — to accomplish this.

1. Line Chart

A line chart displays data as a series of points connected by straight line segments. It is commonly used to show trends over time or to compare changes in values across categories. Matplotlib's plt.plot() function is used to draw line charts. Multiple lines can be plotted on the same graph with different colors and markers for easy comparison.

2. Bar Chart

A bar chart represents categorical data with rectangular bars. The length or height of each bar is proportional to the value it represents. Bars can be plotted vertically or horizontally. Grouped bar charts allow side-by-side comparison of multiple datasets using NumPy's np.arange() for positioning. Value labels can be added to each bar using plt.text() for clearer data communication.

3. Histogram

A histogram is used to visualize the distribution of a single numerical variable by grouping values into bins. Unlike bar charts, histograms represent continuous data. The plt.hist() function creates histograms with configurable bins and styling options. Mean lines can be overlaid using plt.axvline() to provide additional statistical context.

4. Scatter Plot

A scatter plot uses dots to represent the values of two different numerical variables. Each dot's position along the x-axis and y-axis represents a value. Scatter plots are widely used to identify correlations and patterns between variables. Color encoding can be added to represent additional categorical dimensions (e.g., pass/fail status).

5. Seaborn for Enhanced Visualization

Seaborn is a Python data visualization library built on top of Matplotlib. It provides a higher-level interface for creating attractive and informative statistical graphics. Seaborn's functions such as sns.lineplot(), sns.barplot(), sns.histplot(), and sns.scatterplot() automatically handle many stylistic aspects and integrate tightly with Pandas DataFrames.

**Chart Operations**

1. Data Preparation

Two DataFrames were created using Pandas. The first dataset captured daily academic metrics (Study Hours, Marks, Attendance, Sleep Hours, and Assignments Completed) across five weekdays. A second dataset modeled sales data across multiple days, regions, and product categories including Sales, Profit, and Customers.

2. Line Charts (Basic and Advanced)

A basic line chart was plotted to visualize the trend of Study Hours over five days using Matplotlib's plt.plot() with circle markers. An advanced version was then created overlaying two lines — Study Hours and Marks — on the same plot with distinct colors (green and red) and different marker styles (circle and square), along with a legend for clarity.

3. Bar Charts (Basic and Advanced)

A basic bar chart was created to compare Marks across days using plt.bar() with a green color scheme. An advanced version added value labels on top of each bar using plt.text() with a red color and a horizontal grid for readability. A grouped bar chart was also constructed using NumPy's np.arange() to compare Study Hours and Marks side-by-side for each day, with a legend.

4. Histograms (Basic and Advanced)

A basic histogram was plotted for marks data using 5 bins with a light blue color and black edges (alpha = 0.30 for transparency). An advanced histogram was created with 6 bins, a mean line overlay using plt.axvline() in red, a dashed grid on the y-axis, and a legend for context.

5. Scatter Plots (Basic and Conditional)

A basic scatter plot was created to explore the relationship between Study Hours and Marks. A conditional scatter plot was then implemented to encode pass/fail results using color — green for Pass and red for Fail — by mapping a Result column to a list of colors passed to plt.scatter() via the c parameter.

6. Seaborn Visualizations

The same chart types were recreated using Seaborn's higher-level API on the multi-dimensional sales dataset. sns.lineplot() plotted Sales over Days, sns.histplot() visualized the distribution of Sales, and sns.scatterplot() plotted Sales vs. Profit. Seaborn automatically applies aesthetic improvements such as confidence intervals and theme-aware styling.

**Applications of Data Visualization**

•	Business Intelligence: Line and bar charts track KPIs such as revenue, profit, and customer growth over time.

•	Education Analytics: Scatter plots and histograms help analyze student performance and identify at-risk learners.

•	Medical Research: Distribution charts and trend lines assist in monitoring patient outcomes and study results.

•	Sales Dashboards: Grouped bar charts and scatter plots reveal regional performance and correlations between variables.

•	Scientific Computing: Histograms reveal the distribution of experimental data for statistical analysis.

**Conclusion**

The experiment successfully demonstrated the implementation of fundamental data visualization techniques using Python's Matplotlib and Seaborn libraries. By applying line charts, bar charts, histograms, and scatter plots to real datasets, we observed how visual encoding transforms raw numerical data into meaningful, interpretable insights. Advanced chart features such as value labels, mean overlays, color encoding, and grouped layouts further enhance communicative power. Seaborn's higher-level API was shown to simplify the creation of statistically rich and visually appealing charts. These visualization skills form a critical foundation for data analysis, machine learning, and business intelligence applications.
