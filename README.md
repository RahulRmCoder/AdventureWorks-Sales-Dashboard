# AdventureWorks Sales Dashboard

## Project Overview
This Power BI dashboard provides sales analysis for AdventureWorks company. It visualizes key sales metrics across different dimensions including day of week, calendar quarter, geographical distribution, and customer commute distance.

## Features
- **Sales by Day of Week**: Column chart showing sales distribution across weekdays
- **Sales by Calendar Quarter**: Pie chart with customized colors for quarterly analysis
- **Sales by Country**: Map visualization showing geographical sales distribution
- **Sales by Commute Distance**: Funnel chart analyzing sales by customer commute distance

## Data Source
The dashboard uses the AdventureWorksDW database, specifically focusing on the following tables:
- FactInternetSales
- DimDate
- DimCustomer
- DimProduct
- DimSalesTerritory

## Technical Details
- **Power BI Desktop**: Used for creating all visualizations
- **Custom Sorting**: Applied to ensure proper day-of-week ordering
- **Custom Formatting**: Title formatting and color customization for better visual representation

## Setup Instructions

### Database Setup
1. Download the AdventureWorksDW database backup file
2. Restore the database in SQL Server Management Studio
3. Ensure the server has proper permissions configured

### Power BI Report Development
1. Connect Power BI to the SQL Server database
2. Import the required tables
3. Create relationships between fact and dimension tables
4. Develop the required visualizations
5. Apply formatting according to requirements
6. Save the final report as "AdventureWorksSales"

## Visualization Details

### Sales by Day of Week
- Column chart showing SalesAmount vs. EnglishDayNameOfWeek
- Custom sorting applied to show days in correct order (Sunday to Saturday)
- Center-aligned title

### Sales by Calendar Quarter
- Pie chart with CalendarQuarter as legend and SalesAmount as values
- Custom colors: 1st Quarter (Red), 2nd Quarter (Blue), 3rd Quarter (Yellow), 4th Quarter (Green)
- Center-aligned title

### Sales by Country
- Map visual showing SalesTerritoryCountry and SalesAmount
- Size of bubbles represents sales volume
- Center-aligned title

### Sales by Commute Distance
- Funnel chart of CommuteDistance and SalesAmount
- Shows conversion rates across different commute distance categories
- Center-aligned title

## Project Requirements
This project was created as part of the Microsoft Power BI course from Intellipaat, specifically Module 1 Case Study.

## Author
Created by Rahul Rajasekharan Menon

License
This project is licensed under the MIT License - see the LICENSE file for details.
