
# Power BI Bank Project

A brief description of what this project does and who it's for

# Bank-Dashboard


## Problem Statement

Using the TechnoEdge banking dataset, visualize and analyze key metrics such as
customer information (name, age, gender), loan details (amount, status), and daterelated information (month, quarter, fiscal year) using interactive visuals in Power BI. Gain insights into customers, loans, and trends for informed decision-making and strategic planning.


## Objectives
1) To Analyze loan status distribution using a pie chart.

2) To Compare average annual income by gender using a bar chart.

3) To Visualize the trend of monthly debt over time using an area. 

4) To Calculate the total current credit balance and display it in a card visual.

5) Filter data by calendar quarter using a slicer for more focused analysis.

6) To Create a bookmark navigator for easy navigation between different time periods in the calendar.

Customer and loan information in 'Bank Detail', customer demographics in 'Customer
Detail', and date-related information in 'Calendar'. Interactive dashboards provide
insights on loan status, amounts, customer demographics, and time-based trends.

## Steps

### Data Modelling

Creating a relationship between tables in the model view of Power BI using a common column improves the accuracy and reliability of data analysis and visualization.

### Data view

Display all geographical datasets in Power BI along with their corresponding data categories, such as city, country, state, and region.


### DAX Functions

Date Functions
Text Functions
Aggregation Functions
Logical Functions
Aggregate Functions

Total Customers: COUNTROWS('Customers Detail')
Average Annual Income: AVERAGE('Customers Detail'[Annual Income])
Average Monthly Debt: AVERAGE('Bank Detail'[Monthly Debt])
Total Credit Balance: SUM('Bank Detail'[Current Credit Balance])

AVERAGEX('Customers Detail', 'Customers Detail'[Age], 'Customers Detail'[Gender])

SUM('Bank Detail'[Current Credit Balance])

SUM('Bank Detail'[Loan Amount])

Year: = YEAR('Calendar'[Date])
Quarter: = "Q" & FORMAT('Calendar'[Date], "Q")


        
Report Snaps ,

![Capture](https://github.com/Sagarbhar/Power-BI-Banking-Project/assets/168229258/4b4b93ad-2072-4365-bbf3-88944156d44a)

    
