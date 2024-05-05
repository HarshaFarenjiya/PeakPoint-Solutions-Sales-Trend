# DAX Measures used:
<div align="justify">
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
</div>
