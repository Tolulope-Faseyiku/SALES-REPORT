# SALES-REPORT (Tasks and Instructions)

![](sales_picture.png)
## This sales report is created as part of my training exercise, it showcases the ETL process using SQL, analysis and reporting with Power BI dashboarding techniques and documentation using the markdown language.


# Introduction
This is a training exercise with the following tasks:

- Import Database Adveturework2014 into SSMS from the web URL (https://1drv.ms/u/s!AiZu-urEabOdgYIlFcCGIxckz7l6Mg?e=uwNFy0)
- Connect Power BI to SQL Database and import Table Product Transaction History, Sales CurrencyRate, and Sales Order Detail from Database Adveturework2014.

- Using Table Product Transaction History create:
  1. A visual showing the actual Cost for each Transaction Type on a month-to-month.
  2. A table showing the category of Average Quantity into 3 groups, High Quantity, Mid Quantity, and Low Quantity.
  3. A visual showing the total Actual Cost for each Transaction Type.
  4. Create a dashboard for tasks 1, 2, and 3.

- Give an insight into the trend of data in Table Sales Currency Rate, back up insights with visuals
- Design three visuals and an interactive dashboard from Table Sales Sales Order Detail 

# Skills Demonstrated
- ETL process
- Data analysis using DAX queries
- Visualisation in Power BI with page navigation
- Drawing insights from visualisations

### ETL Process
I was able to perform the ETL process by extracting and transforming data with SQL to generate the following tables Product transaction history, Sales currency rate and Sales order details, I also imported the tables into Power BI and used Power Query for transformation and loaded into the Power Bi window to complete the ETL process.

### Data analysis using DAX queries
In analysing the data, I used some simple DAX queries to generate average quantities which helped me group the data and aided my analysis.
![](data_groups.png)

### Visualisation in Power BI with page navigation
I was able to employ some of the skills I learned from Bas, How to Power BI (https://www.youtube.com/@HowtoPowerBI) and ExcelFort (https://www.youtube.com/@ExcelFort) on YouTube which assisted me in formatting my dashboard and visuals in Power BI to get proper white spaces, colour selections and also created page navigation to go through the pages of my Power BI report.

![](page_navigation.png)

### Drawing insights from visualisations
I was able to draw the following insights from the dashboards created from the analysed data:
-  As a result of the incline in the exchange rate in 2011-2013, they need to work towards a reduction in the rate even further than the 2014 rate.
-  VEB the largest of the rates, needs to work towards the exchange rate they had in 2011 of £0.14m
-  JPY is the second largest rate, there was progress in the yearly average rate reduction from 2011 to the current yearly average rate of 2014 of £18k.
-  MXN is the third largest rate and the yearly exchange rate has significantly reduced compared to the starting year of 2011 which was at £2.0k to £1.5k.
-  The current year has experienced a large reduction of the yearly average rate except for VEB, hence these currencies need to drive the rate downwards continually.

### Drawing insights from visualisations
The report was prepared on Microsoft Power BI and it covered three workbooks as instructed. They were named Product Transaction History, Sales Currency Rate and Sales Order Details, they can be viewed in the pbix file SALES REPORT.
