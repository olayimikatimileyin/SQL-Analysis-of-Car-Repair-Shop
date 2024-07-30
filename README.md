Car Repair Shop Operations Project

Overview

This project involves a comprehensive analysis of a car repair shop's operations. The analysis is based on data collected from sample invoices and includes information about customers, vehicles, jobs performed, parts used, and sales receipts. The main goal is to extract meaningful insights using SQL to help the business optimize operations, improve customer satisfaction, and increase profitability.

Project Structure

Part A: Dimensional Model for Sales Analysis

I have attached a PDF Document names Dimensional Model for Sales Analysis to this repositpry and it contained my report to this Part A

The dimensional model for sales analysis is designed to provide a logical business view of the car repair shop's data. The model was created using MySQL Workbench and is documented in the provided PDF.


ER Diagram and Table Descriptions:

Customer Dimension Table (Dime_Customer):

Columns: CustomerID, Name, Address, Phone

Purpose: Stores customer details for demographic and spending behavior analysis.

Vehicle Dimension Table (Dime_Vehicle):

Columns: VehicleID, Make, Model, Year, Color, VIN, RegNumber, Mileage

Purpose: Captures vehicle details to analyze trends in vehicle maintenance.

Job Performed Dimension Table (Dime_JobPerformed):

Columns: JobID, JobDescription, Hours, Rate

Purpose: Lists jobs performed on vehicles to analyze labor performance and costs.

Part Used Dimension Table (Dime_PartUsed):

Columns: PartID, PartNumber, PartName, Quantity, UnitPrice

Purpose: Tracks parts used in repairs for inventory and demand analysis.

Date Dimension Table (Dime_Date):

Columns: DateID, Date, Year, Quarter, Month, Day

Purpose: Facilitates time-based sales analysis.

Location Dimension Table (Dime_Location):

Columns: LocationID, LocationName, Address, City, State, ZipCode

Purpose: Stores shop location details for location-based sales analysis.

Fact Sales Table (Fact_Sales):

Columns: SalesID, CustomerID, VehicleID, JobID, PartID, DateID, LocationID, TotalAmount, SalesTax

Purpose: Aggregates sales data for comprehensive analysis across various dimensions.

Part B: Data Analysis and SQL Queries

I have attached a PDF Document names Car Repair Shop Operation to this repositpry and it detailed contained my report to this Part B


The second part of the project involved importing extended data into a PostgreSQL database and performing various analyses using SQL queries.

Steps:

Data Ingestion and Preparation:

Imported CSV files into the database.

Ensured data cleanliness, proper formatting, and indexing.

Customer Analysis:

Identified top 5 customers by spending.

Calculated average spending per customer
.
Analyzed frequency of customer visits.

Vehicle Analysis:

Calculated average mileage of vehicles serviced.

Identified most common vehicle makes and models.

Analyzed distribution of vehicle ages.

Job Performance Analysis:

Determined most common job types.

Calculated revenue from each job type.

Identified jobs with highest and lowest average costs.

Parts Usage Analysis:

Listed top 5 most frequently used parts.
Calculated average cost of parts.

Determined total revenue from parts sales.

Financial Analysis:

Calculated monthly revenue from labor and parts.
Determined overall profitability.

Analyzed impact of sales tax on total revenue.


Database Setup:

Created tables for customers, vehicles, jobs performed, parts used, dates, locations, and sales receipts.

Ensured referential integrity and proper indexing for efficient querying.


SQL Scripts:

SQL scripts used for table creation and data import are provided.

Detailed SQL queries for each analysis task are documented, along with findings and insights.


Deliverables
Dimensional Model Document:

ER diagram and descriptions of each table and column.

Logical explanations for table creation decisions.


Analysis Report:

Detailed analysis findings and insights.

SQL queries used for data analysis.

Visualizations of key findings (graphs and charts).


Recommendations
Based on the analysis, several actionable recommendations are provided:

Customer Retention:

Implement loyalty programs for top-spending customers.

Increase repeat business through follow-up reminders and maintenance schedules.

Inventory Management:

Maintain a broad inventory of parts to cater to common vehicle makes and models.
Keep higher stock of frequently used parts.

Service Optimization:

Identify underperforming services for improvement or marketing efforts.

Adjust scheduling to better manage frequent job types.

Financial Strategies:

Monitor monthly revenue trends to identify peak and off-peak periods.

Evaluate the impact of sales tax to optimize pricing strategies.


I have attached the invoice i used to create my table for the part A of this analysis, i also attached the datasets i used for the B Part. 
Thank you.
