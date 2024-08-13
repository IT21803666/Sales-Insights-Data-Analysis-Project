# Sales-Insights-Data-Analysis-Project

### Project Background

Atliq hardware is a company which supplies computer hardware and peripherals to many of the clients (different stores). Atliq has its headquarters and many other branches and the challenge that the sales director faces is gathering insights on how the other branches are functioning. Currently, he/she would gather insight details by calling their regional managers but due to the lack of accuracy, completeness and false information they fail to get the much accurate, completed factful insights regarding the business. Therefore, the requirement of the sales director is to get simple, understandable, digestible insights rather than numbers but through a visualization where they could glance and get which information are accurate and complete to make necessary adjustments in Atliq.  

### Project Planning and Data Discovery

In this project, AIMS grid is used as a project planning tool to identify the purpose, stakeholders, end -result and success criteria.
Given below is a draft of the above projects’ AIMS grid.

##### Purpose – to unlock sales insights that are not visible before for sales team for decision support and automate them to reduced manual time spent in data gathering. 
##### Stakeholders – sales director, marketing team, customer service team, data analytics team, IT
##### End-result – an automated dashboard providing quick and latest sales insights in order to support data driven decision making. 
##### Success criteria – dashboards uncovering sales order insights with latest data available, Sales team able to take better decisions and prove 10% cost savings of total spend, Sales analysts stop data gathering manually to save 20% of their business time and reinvest it value added activity	

In this project MySQL acts as the OLTP (Online Transaction Processing) and through the ETL a data warehouse would be built for the data gathering stage which will not affect MySQL since live transactions are happening. 

### Tools and Techniques used

Data analysis was done through MySQL, whereas Data Cleaning and ETL using PowerQuery Editor. Started off with data modelling by mapping the entities which eventually created a star schema with fact table been the sales transactions and the rest been dimension tables. The sales analysis dashboard was created using Power Bi, allowing dashboard to be accessed using the mobile as well. 

### Analysis 

The Sales Analysis dashboard allows the stakeholders to choose a year and a month (optional) to futher analyze information such as revenue, sales quantity, revenue by market, sales quantity by market, top 5 customers as well as products and also the revenue trend. 


