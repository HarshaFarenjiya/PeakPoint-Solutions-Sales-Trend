![importpostgres(1)](https://github.com/HarshaFarenjiya/PeakPoint-Solutions-Sales-Trend/assets/117337376/9640ef4f-356b-4d6e-a4a4-8eb4932e9a25)

# PeakPoint-Solutions-Sales-Trend

## Overview
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

## DAX Measures used:
Following DAX queries provided a comprehensive analysis of sales performance, target achievement, and YTD comparisons, enabling stakeholders to gain valuable insights for decision-making and strategic planning:

1. **Months Target Reached:**
   - This query filtered the 'Calendar' table to identify months where the sales variance (the difference between actual sales and target sales) was greater than zero, indicating that the target had been reached.
   - It returned the count of months where the target was reached.

2. **Target Status:**
   - This query assigned a status code to each month based on whether the variance was greater than zero or not.
   - If the variance was greater than zero, indicating the target was met, it assigned a value of 1. Otherwise, it assigned a value of -1.

3. **Total Sales Actual:**
   - This query calculated the sum of actual sales from the 'Actual' table.

4. **Total Sales Target:**
   - This query calculated the sum of target sales from the 'Targets' table.

5. **Trend_Chart_Title:**
   - This query generated a descriptive title for a trend chart summarizing the target achievement over the specified period.
   - It calculated the total number of months in the calendar and the count of months where targets were met.
   - It returned a string indicating the number of months where targets were met out of the total number of months.

6. **Variance:**
   - This query calculated the difference between total actual sales and total target sales.

7. **Variance %:**
   - This query calculated the percentage variance between actual and target sales.
   - It divided the variance by the total target sales.

8. **Variance Pct Label:**
   - This query generated a formatted label indicating the percentage variance and whether it was positive or negative.
   - It formatted the absolute value of the variance percentage and appended an arrow emoji (up or down) based on whether the variance was positive or negative.

9. **YTD Sales Actual:**
   - This query calculated the year-to-date (YTD) sum of actual sales using the DATESYTD function to filter data from the beginning of the year to the current date.

10. **YTD Sales Target:**
    - This query calculated the YTD sum of target sales.

11. **YTD Variance:**
    - This query calculated the YTD variance between actual and target sales.

12. **YTD Variance %:**
    - This query calculated the YTD percentage variance between actual and target sales.
