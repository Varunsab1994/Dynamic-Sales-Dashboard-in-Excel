# Dynamic Sales Dashboard in Excel

## Overview

![Dashboard_img_file](https://github.com/user-attachments/assets/044affa4-3dea-41c2-8bbb-48a9142fb95a)

This project involves creating a dynamic dashboard in Excel to visualize and analyze sales data. The dashboard includes various charts to provide insights into sales performance across different dimensions such as item type, outlet type, establishment year, and more.

## Features

The dashboard includes the following charts:

1. **Bar Chart (Total Sales by Item Type):**
   - Visualizes total sales for different item types.

2. **Column Chart (Outlet Type vs. Average Sales):**
   - Compares average sales across different outlet types.

3. **Line Chart (Sales Trend over Years for Each Outlet):**
   - Shows sales trends over the years for each outlet.

4. **Scatter Plot (Item Weight vs. Average Sales):**
   - Analyzes the correlation between item weight and average sales.

5. **Pie Chart (Sales Distribution by Item Fat Content):**
   - Displays the distribution of sales across different item fat content categories.

6. **Column Chart (Top 10 Items by MRP and Their Sales):**
   - Highlights the top 10 items by maximum retail price (MRP) and their sales.

7. **Column Chart (Top Outlets by Sales):**
   - Identifies the outlets with the highest total sales.

8. **Line Chart (Average Sales by Establishment Year):**
   - Tracks the average sales by the establishment year of outlets.

9. **Bar Chart (Average Sales by Outlet Location Type):**
   - Compares average sales across different outlet location types.

## Data

The data used in this dashboard includes the following columns:
- `Item_Weight`
- `Item_Fat_Content`
- `Item_Visibility`
- `Item_Type`
- `Item_MRP`
- `Outlet_Identifier`
- `Outlet_Establishment_Year`
- `Outlet_Size`
- `Outlet_Location_Type`
- `Outlet_Type`
- `Item_Outlet_Sales`

## Instructions

### Setting Up the Dashboard

1. **Open Excel:**
   - Open the Excel file containing your data.

2. **Insert PivotTable:**
   - Select your data range.
   - Go to `Insert` > `PivotTable`.
   - Place the PivotTable in a new worksheet.

3. **Create Charts:**
   - Follow the instructions below to create each chart.

### Creating the Charts

1. **Bar Chart (Total Sales by Item Type):**
   - Select the data range for `Item_Type` and corresponding total `Item_Outlet_Sales`.
   - Go to `Insert` > `Bar Chart` > `Clustered Bar`.

2. **Column Chart (Outlet Type vs. Average Sales):**
   - Select the data range for `Outlet_Type` and corresponding average `Item_Outlet_Sales`.
   - Go to `Insert` > `Column Chart` > `Clustered Column`.

3. **Line Chart (Sales Trend over Years for Each Outlet):**
   - Select the data range for `Outlet_Identifier`, `Outlet_Establishment_Year`, and total `Item_Outlet_Sales`.
   - Go to `Insert` > `Line Chart` > `Line`.

4. **Scatter Plot (Item Weight vs. Average Sales):**
   - Select the data range for `Item_Weight` and corresponding average `Item_Outlet_Sales`.
   - Go to `Insert` > `Scatter Plot` > `Scatter with Straight Lines and Markers`.

5. **Pie Chart (Sales Distribution by Item Fat Content):**
   - Select the data range for `Item_Fat_Content` and corresponding total `Item_Outlet_Sales`.
   - Go to `Insert` > `Pie Chart` > `Pie`.

6. **Column Chart (Top 10 Items by MRP and Their Sales):**
   - Select the data range for the top 10 items with highest `Item_MRP` and corresponding `Item_Outlet_Sales`.
   - Go to `Insert` > `Column Chart` > `Clustered Column`.

7. **Column Chart (Top Outlets by Sales):**
   - Select the data range for `Outlet_Identifier` and corresponding total `Item_Outlet_Sales`.
   - Go to `Insert` > `Column Chart` > `Clustered Column`.

8. **Line Chart (Average Sales by Establishment Year):**
   - Select the data range for `Outlet_Establishment_Year` and corresponding average `Item_Outlet_Sales`.
   - Go to `Insert` > `Line Chart` > `Line`.

9. **Bar Chart (Average Sales by Outlet Location Type):**
   - Select the data range for `Outlet_Location_Type` and corresponding average `Item_Outlet_Sales`.
   - Go to `Insert` > `Bar Chart` > `Clustered Bar`.

## Conclusion

This dynamic dashboard provides a comprehensive analysis of sales data, allowing users to gain insights into sales performance across various dimensions. The use of multiple charts helps in visualizing the data effectively and making informed decisions.

## Repository

Feel free to explore the repository and use the dashboard for your data analysis needs. Contributions and suggestions are welcome.

---

**Contact:**
Varun Sabharwal  
[LinkedIn](https://www.linkedin.com/in/varun-sabharwal-54309b74/) | [GitHub](https://github.com/Varunsab1994?tab=repositories)
