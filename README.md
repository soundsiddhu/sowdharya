Project Overview
This project focuses on applying fundamental data science techniques—including synthetic data generation, data cleaning, statistical analysis, and visualization—to a simulated e-commerce environment. By creating a controlled dataset, we can model customer demographics and purchasing patterns to derive actionable business insights.

 Technologies Used
Python 3.x: Core programming language.

Pandas: For data manipulation and structural analysis.

NumPy: For generating synthetic data using statistical distributions.

Matplotlib/Seaborn: For creating informative data visualizations.

 Methodology
1. Data Generation
We programmatically generated a dataset of 500 entries with the following features:

CustomerID: Unique identifier.

Age: Uniform distribution between 18 and 70.

PurchaseAmount: Generated using a Gamma Distribution to simulate realistic spending habits (many small purchases, few large ones).

TransactionFrequency: Monthly count per customer.

Region: Categorical data (North, South, East, West).


Shutterstock
Explore
2. Data Cleaning & Exploration
Verified that the dataset contained no null values.

Confirmed data types (e.g., ensuring Region is treated as a category and Age as an integer).

Documented the structure of the dataframe using df.info().

3. Statistical Analysis
We calculated descriptive statistics for numerical features to understand the "typical" customer profile.

Central Tendency: Mean and Median to identify the "middle" of the data.

Dispersion: Standard Deviation and Quartiles to understand the spread of spending and age.

 Visualizations
The project includes two primary charts:

Purchase Distribution (Histogram): Visualizes how many customers fall into specific spending brackets.

Regional Comparison (Bar Chart): Compares the average transaction frequency across different geographic segments to identify the most active regions.

 
