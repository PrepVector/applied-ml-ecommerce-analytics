### Steps in project
- Problem description
- Import Data in MS SQL Server
- Connecting Power BI to MS SQL DB
- Data Cleaning
- Data Processing
- Data Modelling
- Creating Date Table
- Data Visualization
- Creating Dashboard
- Generating Insights

### Problem Statement
A US Based Ecommerce Sales Company wants us to create a Sales Dashboard to track the performance of YTD Sales and generate insights for below scenarios-

##### Outcomes of Discussions (Solutions)
- Create a KPI Banner showing YTD Sales, YTD Profit, YTD Quantity sold, YTD Profit Margin
- Find Year on Year growth for each KPI and show a YTD sparkline for each measure in the KPI to understand the monthly trend for each fact.
- Find YTD Sales, PYTD Sales, YoY Sales growth for different customer category. Add a trend icon for each category.
- Find YTD Sales performance by each State
- Top 5 and Bottom 5 Products by Sales
- YTD Sales by Region to know best and worst performing region all over country
- YTD Sales by Shipping Type to get the best shipping type percentage

### POWERBI Functionalities we are understanding in this project -
- How to connect Power BI to MS SQL server and Flat Files
- Data Modelling with three tables
- Data cleaning in Power Query
- How to create a Date Table in Power BI
- Time Intelligence function (TOTALYTD, SAMEPERIODLASTYEAR, etc)
- Creating Dynamic and Complex KPI's
- Basic to Advanced Dax Queries
- Conditional Formatting's, Adding dynamic icons in Power BI
- Different DAX functions like Calculate, Sum, Sumx, Filter, values, selectedvalue, return, concatenate, divide, var, etc
- Creating different charts, maps and formatting then
- Generating Insights from charts
- Export report

### Versions used to develop project report
- Power BI - Version: 2.116,966.0, 64-bit (April, 2023)
- MS SQL Server - 19.0.2
- Excel - Office 2021

### Data walkthrough
Original source - Kaggle

Ecommerce data - For analysis
<img width="951" alt="image" src="https://github.com/PrepVector/Applied-ML/assets/82357659/fc1acf23-c9ca-4e29-9731-4c2f516576ff">

US geographical data - longitude, latitude

<img width="259" alt="image" src="https://github.com/PrepVector/Applied-ML/assets/82357659/bc41a3a0-ebe5-407f-9448-c06f3e7708ee">

### Dashboard
<img width="624" alt="image" src="https://github.com/PrepVector/Applied-ML/assets/82357659/9b9bfba9-ab9c-430e-b1fe-a59a189e047a">


**Data model diagram with three connected tables or entities: "ecommerce_data", "us_states", and "Calendar".**

This type of diagram is commonly used in business intelligence tools like Power BI to design and visualize the structure of a data model before creating reports and dashboards based on the integrated data.

The "ecommerce_data" table contains columns category, customer_city, customer_country, customer_first_name, customer_id, customer_last_name, customer_region, customer_segment, and customer_state.

The "us_states" table has columns for latitude, longitude, name, and state.

The "Calendar" table includes columns for Date, Month, Month Number, and Year.

The connections between these tables are represented by the lines and symbols, indicating relationships that allow data to be combined and analyzed across the different entities in the data model.
