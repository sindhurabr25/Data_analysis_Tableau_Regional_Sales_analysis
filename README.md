# Data_analysis_Tableau_Regional_Sales_analysis

## Comparison of Region Based on Sales
### Description
> The director of a leading organization wants to compare the sales between two regions. He has asked each region operators to record the sales data to compare by region. The upper management wants to visualize the sales data using a dashboard to understand the performance between them and suggest the necessary improvements.
 
### Objective:
- Build a region comparison dashboard using Sample Superstore
- Enable dynamic selection of Primary and Secondary regions
- Display key sales and customer insights
- Provide a structured, user-friendly analytical experience
- 
### DataSets Used
- Dataset: Sample Superstore (Tableau’s default dataset)
- This dataset contains details on:
  - Orders
  - Customers
  - Products
  - Geography
  - Sales & Profit metrics

### Steps Performed
1. Data Preparation
 - Connected to Sample Superstore dataset
- Organized Data Source using Group By (Folder) for better structure
- Created a Location hierarchy containing:
- Country → State → City
2. Parameter Creation
- Created two parameters for dynamic region comparison:
   - Primary Region Parameter
   - Secondary Region Parameter
-Both parameters include the full list of regions:
    - Central
    - East
    - South
    - West
- Also created calculated fields to filter data for each selected region.

3. Created a hierarchy for Location
4. created a calculated field to get the first order date.
5. created a calculated filed to get the minium and maxium sales in that sub-caterogy.
6. created bar graph for primary and secondary region.
7. created line chart to show the sales for the sub category.
8. finally created Dashboard to bring all the work book together to shcow the comparison of sales based on the region selected.
 ![Screenshot 2026-03-09 201642](https://github.com/user-attachments/assets/86b8555e-ceb3-421d-826f-c3830b6259d1)

## Dashboard Features
- Dynamic Region Comparison via parameters
- Clean segmentation of Primary vs Secondary region
- Drill-down capability using the Location hierarchy
- Intuitive arrangement of KPIs for quick insights
- Visually appealing charts and metrics for better decision-making

 ## Technologies Used
- Tableau Desktop
- Sample Superstore Dataset
