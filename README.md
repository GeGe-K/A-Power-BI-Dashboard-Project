# A Power-BI Dashboard Project

# Business Intelligence Solution Project

## Project Overview
This project aims to design and deliver an end-to-end business intelligence solution for a client using the CRISP-DM (Cross Industry Standard Process for Data Mining) framework. The client has collected transactional data for the year 2019 but has not been able to leverage it effectively. Our goal is to analyze this data and generate a report that identifies key opportunities to increase sales and improve operational efficiency.

### Business Objectives
The client requires insights on the following key questions:

1. Total Revenue: How much money did we make in 2019?
2. Seasonality: Can we identify any seasonality in the sales?
3. Product Performance: What are our best and worst-selling products?
4. Sales Trends: How do sales compare to previous months or weeks?
5. Geographic Distribution: Which cities are our products delivered to most?
6. Product Categories: How do product categories compare in terms of revenue generated and quantities ordered?
7. Additional Insights: Provide any additional insights that can be derived from the data.

Products with unit prices above $99.99 should be labeled as high-level products; otherwise, they should be categorized as basic-level products.

Data Overview
The dataset is split into two parts:

1. First Half (January to June 2019): Data collected in Excel and saved as CSV files. Available via OneDrive.
2. Second Half (July to December 2019): Data stored in a remote database.

### Database Credentials
Server Name: dap-projects-database.database.windows.net
User: capstone
Password: Z7x@8pM$2w
Database Name: dapDB

### Methodology
The project follows the CRISP-DM framework,as it will provide the client with actionable insights based on their 2019 transactional data, helping them identify opportunities to increase sales and enhance operational efficiency. The use of the CRISP-DM framework ensures a structured and thorough approach to data mining and business intelligence, which involves the following phases:

1. Business Understanding: 
This will involve defining business objectives.

2. Data Understanding: 
In this phase, we will collect initial data, describe the data, and explore the data to identify quality issues.

3. Data Preparation: 
We will clean and prepare the data, including data integration, transformation.

4. Evaluation:

5. Deployment: 
We will use power BI to deliver the final report and recommendations to the client.

## Deliverables
A comprehensive power BI report addressing the client's key questions.
Visualizations and dashboards that highlight key insights.
Recommendations for leveraging the findings to drive more sales and improve efficiency.

### Tools and Technologies
Python/Pandas: For data cleaning, preparation, and analysis.
SQL: For querying the database and extracting relevant data.
Excel/CSV: For handling the first half of the dataset.
Power BI: For data visualization and dashboard creation.
Jupyter Notebook/VS Code: For code development and documentation.

# Getting Started

### Data Access:

Download the first half of the data from OneDrive.
Access the second half of the data using the provided database credentials.
Using a cursor, we execute sql queries to interact with the database and view our second half of the data
cursor = connection.cursor()




