<h1 align="center">Data Analyst Portfolio Project - Sales Management</h1>


![portfolio](https://user-images.githubusercontent.com/87469857/192596619-e4b5fb8f-3bc7-4b61-8e60-e424867370bc.png)
<h3 align="Left">Business Request & User Stories</h3>
The business request for this data analyst project was an executive sales report for sales managers. Based on the request that was made from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria’s were maintained throughout the project.

![Business](https://user-images.githubusercontent.com/87469857/192600101-747379fe-78b0-4510-88c8-799c4d460851.png)

<h3 align="left">Data Cleansing & Transformation(SQL)</h3>
To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using SQL.
One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.
Below are the SQL statements for cleansing and transforming necessary data.

<h6 align="left">DIM_Calendar:</h6>

![Dim_cal](https://user-images.githubusercontent.com/87469857/192603279-0c526c58-90b3-4f02-a42d-40de0cd23557.png)

<h6 align="left">DIM_Customers:</h6>

![Dim_cus](https://user-images.githubusercontent.com/87469857/192602947-f2cdb5c4-1adb-4c52-a0d8-1514baa8e3f0.png)

<h6 align="left">DIM_Products:</h6>

![prod](https://user-images.githubusercontent.com/87469857/192604379-8dc1b76b-50c1-471a-aca7-9255e7ed894b.png)

<h6 align="left">FACT_InternetSales:</h6>

![Internet sale](https://user-images.githubusercontent.com/87469857/192604426-0c3df063-1173-400c-b13c-96c6ecfa20ac.png)

<h6 align="left">Data Model</h6>
Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.
This data model also shows how FACT_Budget hsa been connected to FACT_InternetSales and other necessary DIM tables.

![port3](https://user-images.githubusercontent.com/87469857/192604886-baacf005-7485-4028-b15d-ce2e2fa923ef.png)

<h6 align="left">Sales Management Dashboard</h6>
The finished sales management dashboard with one page with works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.

![por1](https://user-images.githubusercontent.com/87469857/192605274-322373d2-48d8-4822-8858-0f9c72103d58.jpg)


