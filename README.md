![IronHack_Logo](https://user-images.githubusercontent.com/92721547/180667578-7208994e-3fdf-4006-8481-d0723b917662.png)

# Lab | Manipulating Data from Multiple Sources 

Refer to the data source [Adventureworks_Database.xlsx]()
and [Budget_pdf]() in the ``Files for lab`` folder for this lab

### Instructions 
The goal of this lab is to connect data from multiple sources and create visualisations from different tables. 
1. Import the excel file ``Adventureworks_Database`` and connect the following tables using the right relationships
    * Calendar 
    * Sales 
    * Customer
    * Territories
    * Product
2. Plot the following visualisataions using the connected tables in a report: 
    * Quantity of products sold in each region by category 
    * Show total sales amount by year 
    * Show total sales by category and drill down by subcategory to share further insights
    * Use a line chart to show total sales over time by Month. 
3. Now connect the  database ``Budget_pdf`` to your PowerBi workbook. Edit the various column names and merge all tables into one query named ``Budget_pdf``
4. Plot a bar chart comparison of Budget against actual sales and filter out the year 2017. 
5. Open mySQl and create the database classicmodels by running the script ``mysqlsampledata`` located in the ``Files for lab`` folder. Next step is to connect to the SQl database ``classicmodels`` from PowerBI as a new data source and select the follwoing tables: 
    * offices
    * payments
    * products 

Connect ``Classicmodels offices`` table to ``Territories`` table in AdventureWorks and the ``Classicmodels Payments`` table to the ``sales`` table in Adventureworks using the appropriate relationships.

6. Create a report (table) to show countries where both Classicmodels and Adventureworks have offices or operate in ? 
7. Use a bar chart to compare total sales of both companies, filter each company sales to 1 year only.  

### Optional 
1. Plot a visual of any appropriate type showing the percentage difference of actual sales against budget, for each product category in AdventureWorks. (Tip: Create a calculated measure called **variance** and then plot this measure against product category)
