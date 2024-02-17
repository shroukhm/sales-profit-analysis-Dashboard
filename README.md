#      sales & profit analysis  Dashboard 

### Report Link :https://app.powerbi.com/links/yR3-EEDjXk?ctid=77255288-5298-4ea5-81aa-a13e604c30ac&pbi_source=linkShare

## Problem Statement

The data set is about a chocolate company. They provided five months of data for a single year. They want to increase their sales and identify the reason for sales growth.
## Data set: 
I have been provided with a 1910_m4_dataset_v1.0 xlsx file which contains the data divided into four tables: Location, people, products. and sales. Each table contains data related to the chocolate company. 

#### locations table: 

- Geo : It represents the country. 
- Region: Represent the region where the country lies, such as Asia, America, and Europe. 
#### people table: 
- Salesperson: The person who sells a particular product is called a salesperson. 
- Team: The name of the team belongs to a salesperson. (Mummies, Delish, and Juices) 
#### products table:
 - Category: Types of chocolate they made. (Bites, Bars, and Other) 
- Cost per box_ Manutactunng cost of a particular box IN number product)  in dollars. 
- Product: Variants of different types of chocolate. 

#### sales table: 
- Amount: Sales made by the salesperson on a particular day in dollars. 
- Boxes: Number of boxes sold by a salesperson. 
- Customers: Number of different customers who bought that product. 
- Date: Selling date of the product. 
- Geography: It represents the country. 
- Product: Variants of different types of chocolate. 
- Salesperson: The person who sells a particular product is called a salesperson. 

# steps :

- step 1 : Import datasets and create a relationship between them based on standard fields. I. from location (Geo) » sales (geography) IL from people (salesperson) » sales (salesperson) from Product(product) » sales(product)

- step 2 :  Based on the product cost price and the number of boxes sold by the salesperson, find out the cost price, create a new column, and store it in

- step 3 : Create new measures and find the "Total Cost" and "Total Amount". 

- step 4 : Based on "Total Cost' and 'Total Amount" create a new measure, "Total profit' and find "Total Profit Margin" in percentage. 

- step 5 : Create cards for "Total Cost". "Total Amount". "Total profit", and "Total Profit Margin". 

- step 6 : Find out the "Manufacturing Cost" and "Total Selling Amount" by each country. 

- step 7 :  Find out the total boxes sold in each region of the world for each category of chocolate. 

- step 8 :  Find out the total selling contribution by each team

- step 9 : With the help of a line chart, find out the total profit of each category of chocolate by each month.

- step 10 : Find the total selling amount by each day and find a trend

- step 11 : add a slicer for sales person's name and months (Date). 
# Snapshot of Dashboard (Power BI Service)

![3](https://github.com/shroukhm/sales-profit-analysis-Dashboard-/assets/134003439/84a1b971-96ff-4433-984e-21906ecbda40)
