# DataAnalyticsExercise
## Tableau Dashboard
Following this video: https://www.youtube.com/watch?v=NoppQVdd8U8, https://www.youtube.com/watch?v=JEdyVHc-bZk, https://www.youtube.com/watch?v=8_eVFXUGebA&t=4s I created a Sales Dashboard. In the first video we created some calculated fiels that allowed us to create KPIs and Sparkline graphs for Sales, Profit and Qty. Following the second video of the tutorial we created legend for KPIs, we then created a INNER JOIN with hexmap data and created 3 map charts. Following the third video of the tutorial we created monthly sales data by segment graph, total sales by location and manager, filter by category, region, ship mode that is accessed using the filter button and possible to use dark or bright mode.

* Tableau Dashboard: [Click Here](https://public.tableau.com/views/SalesDashboard_16820939723440/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Tableau Dashboard
Following this youtube video: https://www.youtube.com/watch?v=oAIubTqg-Kw&t=8s and this youtube video: https://www.youtube.com/watch?v=oTyCZVnNVZA I created
a dashboard HR Analytics Dashboard.

* Tableau Dashboard: [Click Here](https://public.tableau.com/views/HRAnalyticsDashboard_16814032423450/HRANALYTICSDASHBOARD?:language=en-US&:display_count=n&:origin=viz_share_link)

I improved my knowledge of calculated fields, filters, different chart types and create a parameter Bin Size where I can choose the different age bin in the
No. of Employees by Age Group.

## Water Quality Check

* [Code](https://github.com/rokzupan1/data-analytics-exercise/blob/main/water_quality_check.ipynb)
* [Data](https://github.com/rokzupan1/data-analytics-exercise/blob/main/water_potability.csv)
* [DataMissing](https://github.com/rokzupan1/data-analytics-exercise/blob/main/missing_rows.csv)

## FullDataAnalysisExercise

* [SQL code](https://github.com/rokzupan1/fulldataanalysisexercise/blob/main/SQLQuery2.sql)
* [Excel file](https://github.com/rokzupan1/fulldataanalysisexercise/blob/main/ItemsSalesList.xlsx)
* [Tableau Dashboard](https://public.tableau.com/views/ExecutiveDashboard_16755197372350/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

Following youtube video: https://www.youtube.com/watch?v=1pHYKdyRvrw&list=WL&index=6
I decided to create data analysis. The work is done in SQL, Excel, Tableau.
The data was found in the description of the youtube video.

1. Understand the problem
2. Collect and gather the data
3. Clean the data
4. Gather and Analyze the data
5. Interpret the results

What does the management want?
They want to know the condition of the sales activities within the company.
They want to gain insights into various trends happening in the sales volume
over the 2016-2018 period. They probably also want to know the revenues per
region, per store, per product category. A list of the top 
customers and sales reps could also prove insightful. 

My first problems were that I couldn't connect to server in Microsoft SQL Server
Management Studio because I haven't install SQL Server Express instance. After that
I connected to the server and created objects and load data using dataset that I have
downloaded from youtube video. 

After following the video that created a 4722 long list of items sold with writing
SQL query with functions JOIN, GROUP BY, SELECT, FROM, AS, CONCAT. More items
could be sold in one order, we have connected Excel and our query from database
BikeStores from server localhost. This created a table exactly the same as the
result of the query in MSSMS was. I named this sheet Query1. I added two more sheets
Pivot Table and Dashboard.

While creating charts in Excel I had a problem because my version of Excel didn't
support map charts. I created a map chart in QlikSense. For other graphs there were
no problem and I completed them with Excel. 

Then I connected my table in Excel with Tableau Public and created interactive dashboard
with graphs and filters/slicers. I saved the file in cloud and it is accessible for
everyone. 

## SQLforDataAnalysts
* [SQL Code](https://github.com/rokzupan1/DataAnalyticsExercise/blob/main/SQLforDataAnalyst.sql)
* [Database](https://github.com/rokzupan1/DataAnalyticsExercise/blob/main/SQLite%20Test.db)
* [UNION vs. UNION ALL](https://github.com/rokzupan1/DataAnalyticsExercise/blob/main/UnionVsUnionAll.PNG)

Following the youtube video: https://www.youtube.com/watch?v=gwp3dJUsy5g&list=WL&index=7
I practize some basic SQL functions and learn about some new functions.
I used DBeaver, a SQL client software application and a database administration tool.
I learned about the difference between UNION and UNION ALL. I also refreshed my memory
on JOINS, LIKE, BETWEEN, IN. I also learned new functions: OVER & PARTITION BY, RANK,
ROW_NUMBER, LAG, LEAD.

OVER and PARTITION BY are used in window functions, which are a way to perform a calculation 
across a set of rows that are related to the current row. The PARTITION BY clause is used to 
specify the columns to divide the data into partitions and OVER clause is used to define the 
window frame over which the calculation is performed.

RANK, ROW_NUMBER are types of ranking functions that can be used to assign a unique number 
to each row within a result set, partitioned by one or more columns. ROW_NUMBER assigns a 
unique incremental number to each row, while RANK may assign the same rank to multiple rows 
if there is a tie in the values of the columns specified in the ORDER BY clause.

LAG and LEAD are functions that allow you to access the values of a row within a specific 
offset from the current row, relative to the order specified in the ORDER BY clause. LAG 
returns the value of the row that is n rows before the current row, and LEAD returns the 
value of the row that is n rows after the current row.

For example, you can use the ROW_NUMBER function to number the rows of a result set, the 
LAG function to compare the value of the current row with the previous row, and the LEAD 
function to compare the value of the current row with the next row.

