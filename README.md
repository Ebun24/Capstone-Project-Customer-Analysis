# Capstone Project

## Project Title
Customer Analysis 

## Project Overview
This project utilizes Excel, SQL Server, and Power BI to analyze customer data, focusing on subscription trends, cancellations, and overall performance metrics. The integration of these tools allows for comprehensive data manipulation, visualization, and reporting.

## Data Source
Incubator Hub, Capstone Project

## Tools Used
- **Excel**: For initial data processing and exploratory analysis[Download here](https://www.microsoft.com)
- **SQL Server**: For data storage, transformation, and management.[Download here](https://www.microsoft.com)
- **Power BI**: For creating interactive dashboards and visualizations.[Download here][Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
- **Github for Portfolio Building** (GitHub.com)
  
## Data Cleaning and Preparation
- **Standardize Data Formats**:Remove or impute as needed
- **Calculate Derived Columns**: Add SubscriptionDuration
- **Validate Data Consistency**: Check for negative revenues, date inconsistencies, and ensure positive subscription durations.

## Data Analysis 
The dataset used for this analysis includes the following columns:
- `CustomerID`: Unique identifier for each customer.
- `CustomerName`: Name of the customer.
- `Region`: Geographic region of the customer.
- `SubscriptionType`: Type of subscription (Basic, Standard, Premium).
- `SubscriptionStart`: Start date of the subscription.
- `SubscriptionEnd`: End date of the subscription.
- `Canceled`: Indicates whether the subscription was canceled (TRUE/FALSE).
- `Revenue`: Revenue generated from the subscription.

### Excel
- Analyzed customer data using pivot Tables
- calculated average subscription duration and identified most popular subscription type

### 1. SQL Server Setup 
- **Import Data**:
  - Imported the customer dataset into the created database using SQL Server Management Studio (SSMS).
  
```sql
-- Example SQL script to create a database
CREATE DATABASE CustomerData;
```
## Features
- **Customer Segmentation**: Visualizes the distribution of customers by subscription type and region.
- **Cancellations Analysis**: Displays the proportion of canceled versus active subscriptions.
- **Subscription Trends**: Illustrates monthly trends in new subscriptions over time.
- **Revenue Insights**: Summarizes total revenue generated by different subscription types.
- **Interactive Slicers**: Allows users to filter data dynamically based on regions, subscription types, and cancellation status.

## PowerBI
- **Created Dashboard showing**:
    - Count Of Customers
    - **Canceled vs Active**: Cancled by Customer ID
    - **Subscription Trends**: Subscription Starts by Customer ID 
    - **Revenue Analysis**: Total Revenue by Subscription

 ## Data Visualization
 
 ##Some Calculations carried out in Excel
 ![Average customer data](https://github.com/user-attachments/assets/3c593076-a707-471b-b383-40c96c6d76e7)

 ## Pivot Table
 ![Pivot Table Customer Data 1](https://github.com/user-attachments/assets/d100c9bf-65eb-4fcf-bfae-19819dffa3db)
 ![Pivot Table Customer data 2](https://github.com/user-attachments/assets/aea11aec-ae87-4d19-b617-1569050c7880)

## Charts
![Capstone Proj  Chart 2](https://github.com/user-attachments/assets/03e4b849-9883-405b-a9ec-8bfef683a593)

## SQL 
![Capstone Project Customer data 1](https://github.com/user-attachments/assets/096439dd-6fe7-4b63-bb8e-b84775f18625)

## PowerBI
![Capstone PowerBI Customer Data](https://github.com/user-attachments/assets/a71c5c0c-80cc-4262-b8ad-d080f2e25556)

## Conclusion
This documentation provides a comprehensive overview of the Customer Data Analysis project, detailing the processes involved in utilizing Excel, SQL Server, and Power BI for effective customer segmentation and performance analysis. Through the integration of these tools, we have established a robust framework for analyzing customer behavior, identifying trends, and generating actionable insights.

## Key Takeaways:
-**Data Preparation**: Excel was used for initial data cleaning and exploratory analysis, allowing for the identification of key metrics and segmentation criteria.
-**Database Management**: SQL Server facilitated efficient data storage and management, enabling complex queries to derive insights about customer subscriptions and cancellations.
-**Visual Analytics**: Power BI transformed raw data into interactive visualizations, providing stakeholders with a clear understanding of customer segments, trends, and overall performance metrics.

## Project Outcomes:
The project successfully highlighted significant patterns in customer behavior, including subscription trends and cancellation rates.
The interactive dashboard created in Power BI allows users to dynamically filter data by various dimensions such as region and subscription type, enhancing decision-making capabilities.

## Future Enhancements:
Continuous improvement of the dashboard by incorporating additional data sources or metrics that could provide deeper insights into customer preferences.
Regular updates to the underlying SQL database to ensure that the analysis reflects the most current data available.

## Acknowledgment 
Thank you Incubator Hub for this amazing Opportunity, God bless you. I encourage contributions to this project and welcome any feedback or suggestions for improvement. Thank you for exploring this analysis, and I hope it provides valuable insights into customer behavior! 
