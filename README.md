# LidaAfricaSalesReport_PowerBI
In this project i designed a sales report for a client of Lida Africa displaying key metrics and Key Performance Indicators as per request
## Introduction to the Case
You have just been hired by Lida Africa to design and deliver an end-to-end business intelligence solution from scratch.
Your client needs a way to track KPIs on sales, profit, profit margin, compare regional performance, analyze product-level trends and forecasts, and identify high-value customers.
All you have been given is a CSV file containing information about transactions, products, customers and territories.
To do
We want to know the following KPIs
- Total sales=sum the sales column
- Total Profit=sum the profit column in my dataset
DAX(Data Analysis Expressions)
*% Profit Margin=division total profit/total sales*
*Total customers=countdistinct Customer ID,CountA IDs*
Sum unique IDS 
Primary Keys MUST be text
Class Assignment 
Display the profit/loss trend from Jan to Dec
Create a visual to display the sales and profit margin across all the cities where sales were made.
Create a visual to display profit/loss per category and sub-category.
### DataSet
I cleaned the dataset provided in Microsoft Power query which involved changing datatypes of some columns, removing empty columns and duplicates
I did column profiling to ensure all variables are at 100% without any errors or missing values
## Analysis
I built the data model in the Model view which involved setting relationships, cardinality and cross filter directions
I computed the measures such as total number of customers,Profit Margin, Total Profit and total sales
## Data Visualization
I constructed a line graph to show trend of profits throught the year
A clustered column chart to show profit and Sales by region
A stacked column chart to visualize profi/loss by category and sub category as required
The final project report is available in the files section of the repository.
