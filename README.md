# Amazon Sales Data Analysis

## Overview
This project involves the analysis of Amazon sales data using Python. The analysis focuses on various aspects of sales performance, including regional sales revenue, item type profitability, and sales channel effectiveness.

## Prerequisites
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Preprocessing
1. **Load and Inspect Data**
   - Data is loaded using Pandas and basic inspections like `.head()`, `.columns`, `.shape`, `.size`, `.info()`, and `.describe()` are performed.

2. **Data Cleaning**
   - Checked for missing values using a heatmap.
   - Introduced a missing value for demonstration and filled it with the column mean.
   - Converted date columns to `datetime64` type.

3. **Data Types Conversion**
   - Ensured correct data types for all columns, especially dates.

## Exploratory Data Analysis (EDA)
### Queries and Visualizations

1. **Highest Total Sales Revenue by Region**
   - Grouped data by `Region` and summed `Total Revenue` to identify the highest revenue-generating region.
   - Visualized with a line plot.

2. **Average Unit Price and Unit Cost by Item Type**
   - Calculated average unit price and unit cost per item type.
   - Displayed results in a DataFrame.

3. **Country with the Highest Total Profit**
   - Grouped data by `Country` and summed `Total Profit`.
   - Visualized with a bar plot.

4. **Order Priority Distribution by Sales Channel**
   - Analyzed how `Order Priority` is distributed across different `Sales Channels`.
   - Visualized with a bar plot using `hue` to differentiate priorities.

5. **Average Order Processing Time by Sales Channel**
   - Calculated the average time between `Order Date` and `Ship Date` for each sales channel.
   - Visualized using a bar plot.

6. **Highest and Lowest Total Sales by Item Type**
   - Identified item types with the highest and lowest `Total Revenue`.
   - Highlighted in a scatter plot.

7. **Order Priority Variation Across Regions**
   - Analyzed how `Order Priority` varies across different regions.
   - Visualized with a bar plot.

8. **Correlation Between Unit Price and Total Profit**
   - Calculated the correlation coefficient between `Unit Price` and `Total Profit`.
   - Visualized with a scatter plot.

9. **Seasonal Trends in Sales Data**
   - Analyzed monthly sales data to identify seasonal trends.
   - Visualized using a bar plot.

10. **Units Sold Variation Across Countries**
    - Grouped data by `Country` to sum the `Units Sold`.
    - Visualized using a bar plot.

## Additional Analysis
- Investigated outliers in `Total Cost` distribution using a boxplot.
- Explored relationships between different variables, including the correlation between `Units Sold` and `Total Profit`.

## Conclusion
This analysis provides insights into sales performance across various dimensions. The visualizations and data-driven approach help in understanding key factors influencing sales and profitability.

## Future Work
Further analysis could include:
- Predictive modeling for sales trends.
- Deeper analysis of customer behavior based on historical data.

## How to Run
1. Clone the repository.
2. Install required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.
3. Run the Jupyter notebook or Python script to perform the analysis.

