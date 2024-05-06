![importpostgres(1)](https://github.com/HarshaFarenjiya/PeakPoint-Solutions-Sales-Trend/assets/117337376/9640ef4f-356b-4d6e-a4a4-8eb4932e9a25)

# PeakPoint-Solutions-Sales-Trend
<div align="justify">
   
## Introduction
PeakPoint Solutions, a hypothetical company specializing in sales solutions, maintains a comprehensive dataset to track the performance of its sales team. This dataset, structured within an Excel workbook, encompasses four distinct worksheets, each serving a specific purpose in analyzing sales data, setting targets, and providing supplementary information about the sales personnel.

## Project Purpose
The purpose of this project was to utilize Power BI software to provide valuable insights to the company. By leveraging Power BI's capabilities, the project aimed to analyze data effectively, uncover meaningful trends, and generate actionable insights. These insights were intended to inform decision-making processes, improve operational efficiency, and drive strategic initiatives within the company. Ultimately, the project sought to empower stakeholders with data-driven information that would facilitate informed decision-making and contribute to the company's overall success.

## About the Dataset
### Worksheet 1: Actual
The first worksheet in the workbook titled "Actual" comprises columns dedicated to recording the sales performance of individual salespersons across different months. The columns represent consecutive months starting from January 2023 to February 2024. Each row corresponds to a salesperson, with their sales figures recorded in the respective month columns. The layout facilitates a granular analysis of sales performance over time.

### Worksheet 2: Targets
The second worksheet, labeled "Targets, outlines the sales targets set for each salesperson over the same timeframe covered in the actual sales data worksheet. Similar to the first worksheet, this sheet features columns representing months from January 2023 to February 2024. However, instead of actual sales figures, these columns contain the predetermined sales targets assigned to each salesperson. This sheet enables the comparison between actual sales and set targets, providing insights into individual performance against goals.

### Worksheet 3: Calendar
The third worksheet, titled "Calendar", serves as a reference sheet, listing the sequential dates from January 2023 to February 2024. Each date is recorded in a single column, facilitating chronological alignment with the sales data and target sheets. This sheet aids in maintaining consistency across the workbook and supports temporal analysis of sales trends and target achievements.

### Worksheet 4: DimPeople
The fourth and final worksheet, named "DimPeople," provides supplementary details about the sales team members. It consists of three columns: 
- **Sales Person**: This column contains the names of individual salespersons.
- **Team**: Here, the corresponding teams to which the salespersons belong are listed. This information offers insights into team structures and organizational hierarchies within PeakPoint Solutions.
- **Picture**: The third column contains URLs linking to images of the respective salespersons. These visual representations serve to personalize the dataset and facilitate easy identification of team members.

## Data Pre-processing

### 1. Promotion of Headers:
- The first row of data in each sheet has been promoted as headers. This step assumes that the first row contains column headers, facilitating better readability and interpretation of the data.

### 2. Correction of Data Types:
- Data types across columns have been standardized and corrected as needed. This ensures consistency in data representation and prevents potential errors during analysis.

### 3. Reshaping Data:
- In the Actual and Target sheets, data has been reshaped by unpivoting columns except for the "Sales Person" column. This transformation converts the data from a wide format to a long format, facilitating easier analysis.

### 4. Column Renaming:
- Column names have been adjusted for clarity and consistency across all sheets. This makes it easier to understand the content of each column and ensures uniformity in naming conventions.

### 5. Addition of New Columns:
- In the Date sheet, additional columns for "Year", "Month", and "Month Name" have been derived. This enhancement provides further insights into the temporal aspects of the data.

</div>
