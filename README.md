# Super Store Sales Insight Power-BI-Dashboard

## Problem statement

The superstore is selling a variety of products across multiple countries, with different categories and subcategories.
The goal is to analyze the sales data and identify useful insights to help the store increase its sales and grow its business.

## Steps Followed in this project

Step : 1 
		Business requirement (business requirement document) From the client

Step : 2
		Collect the data from different sources.

		1.	Sales (folder by year)
		2.	Categories (Excel)
		3.	Geography (Excel)
		4.	Product (CSV / Database)
		5.	SalesRep (Excel)
		6.	SubCategories (Excel)
Step : 3 
		Cleaning the data in power query editor

		- Remove the duplicate rows
		- Check the datatype of the column and correct
		- Remove the unwanted columns
		- Extract the data from the column,split the column
		- Concate the the columns,delete the rows
        - Pivot and unpivoting the data

Step : 4
		Create the DIM and Fact Table from the data with the use of DAX Function and Measure
		
		1. Use various Dax function and Measure
		2. Aggregation function
		3. Date and time function
		4. FILTER FUNCTION 
		5. logical function

Step : 5
		Data Modeling :
				  Connect the DIM and FACT table to each other 

Step : 6 
		Create the Dashboard as per the requirement

		Charts Use : 
				Column chart
				Clustered Column Chart
				Pie and Donut Chart
				Waterfall Chart
				Line Chart
				Card and Slicer

## Final Dashboard

![Power BI Dashboard](https://user-images.githubusercontent.com/121163709/235293500-564c656d-8594-4328-b31b-e636c0c1c31a.png)


## Conclution : 
		
In terms of revenue, the extra subcategory and special category are significant contributors with 50% and 65% respectively. 
Among all the products, Quad stands out as the highest profitable one. Germany emerges as the top-performing country generating both high revenue and profit.

Further analysis reveals that the third quarter is the highest revenue-generating quarter. Moreover, the months of January, March, December, and July are the highest profit-generating months. In contrast, the months of November, August, and February are the worst performing months in terms of profit.

## Suggestions : 
		
To improve profits the store should focus on the months like Nov,Aug,Feb and shift its focus to countries beyond Germany and prioritize at least four profitable products that have remained consistent in generating revenue over the past four years.


