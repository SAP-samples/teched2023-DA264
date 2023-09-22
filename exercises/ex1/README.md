# Exercise 1 - Build and expose data views on SAP Datasphere

In this exercise, your objective is to create and display data views on SAP Datasphere by utilizing predefined views from BigQuery and SAP S/4HANA. This process involves leveraging the rich data stored in BigQuery and integrating it into your SAP Datasphere for analysis and reporting purposes. At the end of the exercise, the created views will be exposed and can be accessed from SAP Analytics Cloud(SAC) to build interactive dashboards and generate valuable insights. By combining the capabilities of SAP Datasphere and SAP Analytics Cloud, you can gain a holistic view of your data, facilitating well-informed decision-making.


## Exercise 1.1 Creating a new view of "Product Sales Country"

The exercise is to build a new data view called **"Product Sales Country"** by combining and aggregating the **"Sessions Hits by Country"** and **"Product Sales"** views. This involves joining the two views to create a holistic view of the sales data and aggregating it by country to provide insights into product sales trends by location.

To achieve this, you will need to perform the following steps:

1. Create an inner join of the "Product SKU Transactions" and "Product Sales" data to combine the two views and create a comprehensive view of the sales data
   >HINT: you need to map following attributes: DATE, Product_SKU, transaction_id
2. Add a formula with a new calculated property to further enhance the insights generated from the data
   >HINT: the formula should add new column "DATESTR" which converts datatype DATE to NVARCHAR -> TO_NVARCHAR(DATE, 'YYYYMMDD')
3. Join the projection with the "Hits by Session Country" table to provide a complete picture of product sales by location
   >HINT: you need to map following attributes: Country and DAESTR/DATET
4. Create an **Association** of the final view to **Time Dimension - Day**
   >HINT: you need to map following attribute: DATE

Your goal is to navigate through these steps and create a detailed data view that effectively portrays the trends in product sales based on geographical locations. Best of luck!

## Exercise 1.2 Sub Exercise 2 Description

## Summary

You've now ...

Continue to - [Exercise 2 - Exercise 2 Description](../ex2/README.md)

