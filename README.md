# LITA_Capstone_Project

## Project Title: Data Analysis

Data analysis is the process of collecting, organizing, transforming, and interpreting data to discover useful information, draw conclusions, and support decision-making. At its core, data analysis is about making sense of raw data to uncover patterns, trends, relationships, or insights that can inform strategies, solve problems, or answer specific questions.

- - -
### Steps Invoved in Data Analysis

1. Data Collection: Gathering data from various sources, which might include surveys, databases, logs, or external sources like public datasets or APIs. The quality and relevance of 
   data 
   collected here play a major role in the effectiveness of the analysis.

2. Data Cleaning: This is often the most time-consuming step. Cleaning involves removing or correcting errors, handling missing or inconsistent data, and transforming data into a format 
   suitable for analysis. Clean data is essential for reliable insights.

3. Exploratory Data Analysis (EDA): This involves examining the data using statistical methods, visualizations, and summaries to understand its basic properties and identify any initial 
   trends or outliers. EDA helps analysts understand data distributions and relationships between variables.

4. Data Transformation and Modeling: Depending on the analysis goal, data may be transformed or engineered to reveal insights. Statistical or machine learning models may be applied to 
   uncover deeper patterns, make predictions, or segment the data into groups.

5. Interpretation and Reporting: The final insights are interpreted and communicated, often using data visualizations, dashboards, or reports. This step translates technical findings 
  into actionable insights for decision-makers or stakeholders.

Data analysis is used across various fields, from business and healthcare to marketing and social sciences, to drive informed decisions, improve operations, understand customer behaviors, or forecast future outcomes.
- - -
### Project Overview
---
In this project, our goal is to dive into a dataset and discover the story it tells. Whether we’re looking at customer behavior, sales trends, or operational data, the aim is to turn raw numbers into meaningful insights. By analyzing this data, we’re not only answering specific questions but also revealing patterns and trends that may inform future decisions.

---
### Project Datasets

This project includes two main datasets: the Sales Data and the Customer Data. Together, they provide a comprehensive view of the sales activity and customer engagement, allowing for an in-depth analysis of purchasing behaviors, product performance, and customer loyalty.

---
### Data Description
---

#### Sale Data

This dataset captures details about individual sales transactions. Each row represents a unique order, showing what products were sold, in what quantities, and to which customers.

#### Description

 * OrderID: Unique identifier for each order.

 * Customer Id: ID linking each sale to a specific customer.

 * Product: The type of product sold, such as “Shirt” or “Shoes.”

 * Region: Geographical area where the sale took place (e.g., North, South).

 * OrderDate: Date the order was placed.

 * Quantity: Number of units sold.

 * UnitPrice: Price per unit of the product.

Total Sales: Total value of the sale (calculated as Quantity x UnitPrice).  

----
#### Customer Data

 This dataset provides information about customers and their subscription status, helping us understand customer profiles, subscription types, and customer retention.
 
#### Description:

 * CustomerID: Unique identifier for each customer.

 * CustomerName: Name of the customer.

 * Region: The region where the customer is based (matching with the region in Sales Data).

 * SubscriptionType: Type of subscription plan the customer is on (e.g., Basic, Premium, Standard).

 * SubscriptionStart and SubscriptionEnd: Dates marking the start and end of the subscription period.

 * Canceled: Indicates if the customer canceled their subscription (Yes/No).

 * Revenue: Total revenue generated from the customer.

 * Subscription Duration: Length of the subscription in days.

---
### Purpose of These Datasets

The Sales Data helps us analyze sales performance across regions and products, while the Customer Data reveals customer behavior, loyalty, and subscription trends. Together, these datasets allow for a thorough analysis of customer purchasing patterns and product success, which can drive business strategies and improve customer retention.

---
### Project Objectives for the Datasets

This project uses two key datasets—Sales Data and Customer Data—to explore and analyze different aspects of the business. Each dataset serves specific objectives, helping us gain insights into sales performance, customer behavior, and overall business trends.

---
#### Objectives of the Sales Data

The Sales Data dataset captures transaction-level details for each order. Our objectives with this dataset include:

 * Analyze Product Performance: Identify top-selling products and those with low sales across different regions. This helps us understand which products are driving revenue and which 
   may need promotion or discontinuation.

 * Explore Regional Sales Trends: Examine how sales vary by region to help guide targeted marketing efforts and product distribution strategies. Understanding regional preferences can 
   help tailor offerings to meet customer demand.

 * Track Seasonal or Time-Based Trends: Identify any spikes or dips in sales during specific times of the year. Seasonal trends provide insights into optimal times for promotions or 
   inventory adjustments.

 * Calculate Revenue Metrics: Assess overall sales volume, average order value, and total revenue generated. These metrics help gauge business health and identify revenue drivers.

---
#### Objectives of the Customer Data

The Customer Data dataset provides details on customer profiles and subscription statuses. Our objectives with this dataset include:

 * Analyze Customer Loyalty and Retention: Investigate subscription durations and cancellation rates to understand customer loyalty. This insight helps in developing strategies to 
   improve retention rates, particularly among customers at higher risk of canceling.

 * Segment Customers by Subscription Type: Compare behaviors and revenue generation across different subscription types (e.g., Basic, Premium). Understanding these differences allows 
   for tailored marketing and upselling strategies.

 * Measure Revenue Per Customer: Assess individual customer contributions to total revenue, identifying high-value customers and potential areas for growth among lower-value customers.

 * Understand Regional Customer Demographics: Examine where customers are located to better understand market penetration in different regions, which may inform future expansion or 
   localized marketing efforts.

 ---
### Key Metrics
   
By tracking these metrics, this analysis aims to provide a well-rounded view of both sales and customer engagement. The Sales Data metrics help identify top products, revenue patterns, and regional differences, while the Customer Data metrics provide insights into loyalty,cancellation rate and revenue contributions by customer segments. Together, these metrics will guide data-driven strategies to enhance sales, improve customer retention, and optimize business growth.

---
#### Key Metrics for the Sales Data

The Sales Data dataset provides transaction-level details, allowing us to track important sales and revenue metrics. 

 - Total Revenue: Sum of all sales across all orders. This metric helps gauge overall business income and track revenue growth over time.

 - Average Order Value (AOV): Total revenue divided by the number of orders. AOV helps assess the average amount customers spend per transaction, which is useful for measuring customer 
    purchasing power.
   
 - Product Sales Volume: The total number of units sold for each product. This metric shows which products are most popular and which may need more promotion.

 - Sales by Region: Total sales and units sold per region. Analyzing sales by region helps us understand geographic trends and allows for region-specific marketing or inventory 
   adjustments.
  
 - Sales Over Time: Monthly or quarterly sales trends. Tracking sales over time reveals seasonal patterns or growth trends that can inform marketing and inventory decisions.

---
#### Key Metrics for the Customer Data

The Customer Data dataset offers information on customer profiles and subscription patterns. The following metrics are central to understanding customer engagement and retention:

 - Customer Lifetime Value (CLV): Total revenue generated by each customer over the duration of their subscription. CLV helps identify high-value customers and supports targeted loyalty 
   efforts.

 - Cancellation Rate: Percentage of customers who cancel their subscription within a certain period. Churn rate is essential for measuring customer retention and developing strategies 
   to reduce cancellations.

 - Subscription Duration: Average length of time customers stay subscribed. This metric helps us understand customer loyalty and the effectiveness of subscription plans.

 - Revenue by Subscription Type: Total revenue generated from each subscription tier (e.g., Basic, Premium). This metric shows the financial impact of each plan and informs pricing or 
   upselling strategies.

 - Customer Demographics by Region: Number of customers and revenue contribution by region. This metric highlights where the customer base is most active and supports decisions on 
   regional marketing efforts.

---
### How to Use the Data

#### Sales Data Analysis

1. Product by Total Sales: Group the data by Product and sum the Total sales column. To identify top-selling products based on total Sales.

2. Region by Total Sales: Group the data by Region and sum the Total sales column. To determine which regions contribute most to total sales.

3. Product by Average Sale: Group the data by Product and sum the Average sales column. To Assess the average sale value per product to understand product pricing and customer spending 
   behavior.
   
4. Months by Total Sales: Group the data by Months and sum the Total sales column. To Analyze monthly trends to identify seasonality or sales peaks.

5. Years by Total Sales:  Group the data by Years and sum the Total sales column.To track annual growth and compare year-over-year performance.

---

#### Customer Data Analysis

1. Subscription Type by Subscription Duration: Group the data by Subscription Type and sum the Subscription Duration column. To evaluate how long customers stay subscribed based on 
   subscription type. This insight helps understand loyalty differences across subscription tiers.

2.  Region by Subscription Type by Revenue: Group the data by Region,then Subscription Type and sum the Subscription Duration column. To evaluate how long customers stay subscribed 
    based on subscription type.

3.  Customer ID by Revenue: Group the data by CustomerID and sum the Revenue. To identify high-value customers and their revenue contributions.

4.  Subscription Type by Canceled by Revenue: Group the data by subscription Type,then Canceled and sum the Revenue column.To examine revenue impact from cancellations by 
    subscription type. This highlights revenue lost by cancellations per subscription type, informing retention strategies.

5. Region by Subscription Duration by Revenue: Group by Region, then by Subscription Duration, and sum Revenue. To analyze subscription duration and revenue by region.

### Formula Used

Total Sales = Quantity x UnitPrice).  

Average Sales per Product = AVERAGEIF(C:C,"Socks",H:H)

Total Revenue by Region = SUMIF(D:D,"East",H:H)

Average subscription = AVERAGE(I:I)

Most Popular Subscription Type = =SUMIF(D:D,"Basic",H:H)

Average Revenue = Total revenue/units sold. 
   
### Tools Used
---
 * Microsoft Excel for analyzing data
 * SQL (Structured Query Language) for query,retrieve, insert, update, and delete data stored in database tables
 * PowerBI for Visaualising data
---
#### Microsoft Excel
---
Microsoft Excel is a popular spreadsheet software that helps individuals and organizations organize, analyze, and visualize data. It’s part of Microsoft’s Office Suite and is widely used for everything from simple data storage to complex data analysis and automation.

#### Key Features of Microsoft Excel:
---
* Spreadsheets and Tables: Excel organizes data in a grid of rows and columns, where each cell can hold text, numbers, or formulas. You can create tables, sort and filter data, and 
  apply different formats.

* Data Visualization: Excel offers charts, graphs, and conditional formatting to help users visualize data trends and patterns. From bar charts to scatter plots, Excel provides manyways 
  to represent data visually.

* PivotTables and PivotCharts: These tools allow you to summarize large datasets by aggregating, filtering, and organizing data into meaningful reports.

* Data Analysis and Modeling: Excel includes tools like data validation, data analysis toolpacks, and what-if analysis features, which help with deeper data insights and modeling.

* Automation with Macros and VBA: Users can automate repetitive tasks with macros or create more advanced automation using Visual Basic for Applications (VBA).

* Integration with Other Tools: Excel can connect with databases, cloud services, and other Microsoft Office tools like Word and PowerPoint. It also integrates with Power BI for 
  enhanced data analytics and visualization.

### SQL (Structured Query Language)
---
SQL (Structured Query Language) is a standardized programming language used to manage and manipulate relational databases. It allows users to create, read, update, and delete data in a database, commonly referred to as CRUD operations. SQL is essential for data analysts, database administrators, and developers, as it provides a straightforward way to retrieve specific data from large datasets and perform complex queries efficiently.

#### Key Features of SQL:
---
 * Data Retrieval: SQL allows for precise data querying using commands like SELECT, WHERE, JOIN, and GROUP BY.
   
 * Data Manipulation: Commands like INSERT, UPDATE, and DELETE let users manage database entries.
   
 * Data Definition: With commands like CREATE TABLE and ALTER TABLE, SQL enables schema design and database structure definition.
   
 * Data Control: Commands like GRANT and REVOKE help manage database permissions and security.
   
 * Relational Data Handling: SQL supports joining tables, making it possible to retrieve and analyze data across multiple tables.
   
 * Aggregate Functions: Functions like SUM, AVG, COUNT, MIN, and MAX allow users to perform calculations on data sets.

### Power BI 
---
PowerBI is a business analytics tool by Microsoft designed for data visualization and business intelligence. It enables users to connect to multiple data sources, transform and model data, and create interactive reports and dashboards. Power BI is widely used by data analysts, business intelligence professionals, and decision-makers to extract insights from data in a visually accessible and easy-to-share format.

#### Key Features of Power BI
Power BI offers a range of powerful features that make it a top choice for data analysis and visualization. Here are its key features:

---
 - Data Connectivity and Integration:

   * Multiple Data Sources: Power BI allows you to connect to a wide range of data sources, including databases (SQL, Oracle, etc.), online services (Salesforce, Google Analytics), 
     cloud storage (Azure, AWS), and file types (Excel, CSV, JSON).
     
   * Data Blending: With Power Query, Power BI enables users to combine, clean, and transform data from various sources, ensuring seamless data integration.
     
- Data Modeling:

  * Relationship Management: Power BI supports creating and managing relationships between different tables, similar to a relational database, allowing for robust data models.
    
  * DAX (Data Analysis Expressions): DAX is Power BI’s formula language, providing advanced calculations and aggregations. Users can create calculated columns, measures, and custom 
    formulas to drive detailed insights.
    
- Interactive Visualizations:

  * Wide Range of Visuals: Power BI offers various chart types, including bar, line, scatter, and pie charts, along with unique visuals like maps, gauges, and waterfall charts.
    
  * Custom Visuals: Users can import custom visuals from the Power BI marketplace or create their own, giving flexibility for unique data presentation.
    
  * Drill-Down and Drill-Through: Power BI’s interactive drill-down features allow users to explore data at multiple levels, while drill-through features provide detailed insights by 
    moving from one report page to another.

 - Reports and Dashboards:

  * Real-Time Dashboards: Power BI supports real-time data updates, allowing users to create live dashboards for dynamic tracking of business metrics.
    
  * Cross-Filtering and Slicing: Users can add slicers to filter data in specific ways and apply cross-filtering across visuals, making reports interactive and allowing for tailored 
    views.
 - Power BI Service and Sharing:

   * Cloud-Based Sharing: Power BI Service (the cloud component) enables users to share and collaborate on reports and dashboards with teams or clients. Users can control access 
     permissions and manage report visibility.
     
   * Power BI Mobile: Power BI’s mobile app allows users to access reports and dashboards on the go, ensuring flexibility and accessibility for real-time insights.
     
 - AI and Advanced Analytics:

   * AI Visuals: Power BI integrates AI visuals, such as Q&A (Natural Language Query), Key Influencers, and Decomposition Tree, allowing non-technical users to gain insights with simple 
    questions or to explore drivers of specific outcomes.
    
   * Predictive Analytics: Users can integrate Power BI with Azure Machine Learning for predictive insights, making it a powerful tool for forecasting.
    Embedded Analytics and API Access:

- Power BI Embedded: This feature enables developers to embed Power BI reports and dashboards into custom applications, providing a seamless experience for end users.
   
   * APIs for Automation: Power BI offers REST APIs that allow for automated data refreshes, report generation, and embedding, supporting various business workflows.
     
 - Data Security:

   * Row-Level Security (RLS): Power BI supports RLS, allowing users to control access to data at the row level, so only authorized users see specific subsets of data.
     
   * Data Encryption and Compliance: Power BI complies with numerous data protection regulations and provides encryption, ensuring that sensitive data remains secure.

### Visual Analysis and Inference 
---
### Sale Data Analysis
---
#### 1. Product by Total Sales

#### Pivotal Tables:
![Screenshot 2024-11-05 212521](https://github.com/user-attachments/assets/9b2afc79-218a-4bc7-9cd3-cbffbf89f61a)

---
#### 2.Region by Total Sales

#### Pivotal Tables:
![Screenshot 2024-11-05 212340](https://github.com/user-attachments/assets/eb6d7415-17df-4563-af4e-60fb5ab9ba39)

---
#### 3. Product by Average Sale

#### Pivotal Tables:
![Screenshot 2024-11-05 212444](https://github.com/user-attachments/assets/664a5a69-e9f5-4908-8664-6e396249d198)

---
#### 4. Months by Total Sales

#### Pivotal Tables:
![Screenshot 2024-11-05 212412](https://github.com/user-attachments/assets/61c22642-d629-471c-9981-8822e9303cbd)

---
#### 5. Years by Total Sales:

#### Pivotal Tables:
![Screenshot 2024-11-05 212550](https://github.com/user-attachments/assets/adda3d03-16e3-4316-acee-3bd7fd44fc45)

### Customer Data Analysis




