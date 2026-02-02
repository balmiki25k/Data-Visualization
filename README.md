# Data-Visualization

# Student Data Analysis and Visualization for File `data_visualization.ipynb`: 


This notebook performs an exploratory data analysis on a student dataset `student_dataset_with_visualization.csv`, focusing on data cleaning and visualization.


## Table of Contents
1. [Import Libraries](#import-libraries)
2. [Read Data File](#read-data-file)
3. [Check for Null and Duplicate Values](#check-for-null-and-duplicate-values)
4. [Replace Null Values with Mean](#replace-null-values-with-mean)
5. [Graph by Gender vs. Average Attendance](#graph-by-gender-vs-average-attendance)
6. [Bar Chart for Average Marks in Each Subject](#bar-chart-for-average-marks-in-each-subject)
7. [Pie Chart for Proportion of Grades by Subject](#pie-chart-for-proportion-of-grades-by-subject)


## 1. Import Libraries
This section imports necessary libraries like `matplotlib.pyplot`, `numpy`, and `pandas` for data manipulation and visualization.


## 2. Read Data File
The dataset `student_dataset_with_visualization.csv` is loaded into a pandas DataFrame.


## 3. Check for Null and Duplicate Values
Before analysis, the notebook checks for any missing values (`NaN`) and duplicate rows to ensure data quality.


## 4. Replace Null Values with Mean
Missing values in the 'Marks' column are imputed by replacing them with the mean of the 'Marks' column.


## 5. Graph by Gender vs. Average Attendance
A bar chart is generated to visualize the average attendance percentage based on gender, providing insights into potential differences.


## 6. Bar Chart for Average Marks in Each Subject
This section creates a bar chart displaying the average marks obtained in each subject, allowing for a comparison of subject difficulty or student performance across subjects.


## 7. Pie Chart for Proportion of Grades by Subject
Pie charts are created to illustrate the distribution of grades (A, B, C) within each subject, offering a clear visual breakdown of student achievement levels.




# Sales Data Analysis and Visualization for File `data_vis_task.ipynb`: 


## Overview
This notebook performs an exploratory data analysis on sales training data loaded from an Excel file. The primary goal is to understand sales patterns, revenue distribution across products, daily sales trends, and weekly product-wise revenue performance.


## Data Source
The analysis is based on the `sales_training_data.xlsx` file, which contains sales records including `Date`, `Product`, `Units`, and `Price`.


## Analysis Steps


1. **Import Libraries**: Essential libraries like pandas, matplotlib, and numpy are imported.
2. **Data Loading**: The `sales_training_data.xlsx` file is loaded into a pandas DataFrame.
3. **Data Preprocessing**:
   *  Null and duplicate values are checked (none found).
   *  A 'Revenue' column is calculated (`Units` * `Price`).
   *  The 'Date' column is converted to datetime objects.
4. **Revenue Analysis (Product-wise)**:
   *  Total revenue per product category is calculated.
   *  A bar chart visualizes product-wise revenue.
   *  A pie chart shows the proportion of total sales by product.
5. **Sales Trend Analysis (Daily)**:
   *  Daily total revenue is calculated.
   *  A line graph displays the daily sales trend.
6. **Units Sold Analysis (Category-wise)**:
   *  Total units sold per product category are calculated.
   *  A bar chart visualizes the total units sold for each product category.
7. **Weekly Product Revenue Subplots**:
   *  A 'Week' column is derived from the 'Date' column.
   *  Product-wise revenue is calculated for each week.
   *  Subplots are generated to show weekly revenue distribution for each product category.


## Key Findings


### Units Sold per Product Category:
*  'Mobile' and 'Tablet' products had the highest total units sold, both at 30 units.
*  'Laptop' products followed closely with 27 units sold.
*  This indicates a relatively balanced demand across the product categories, with a slight edge for mobile and tablet devices in terms of unit sales.


### Weekly Product-wise Revenue:
*  The subplots revealed dynamic fluctuations in product revenue across different weeks.
*  **Week 1**: 'Mobile' revenue was the highest.
*  **Weeks 2 and 3**: 'Laptop' revenue dominated, indicating strong performance.
*  **Week 4**: 'Mobile' revenue saw a significant increase again.
*  Overall, 'Laptops' appear to be high-value items, generating substantial revenue, often outperforming other categories in specific weeks, even if their unit sales are slightly lower than 'Mobile' and 'Tablet'.
*  'Tablets' also showed consistent revenue contributions throughout the weeks.


## Technologies Used
*  Python
*  Pandas (for data manipulation and analysis)
*  Matplotlib (for data visualization)
*  NumPy (for numerical operations)
