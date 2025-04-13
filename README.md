
Energy Consumption Analysis: AWS + Snowflake + Power BI 
Project Overview:
This project analyzes energy consumption patterns using cloud-based data architecture and business intelligence tools. By leveraging Amazon S3, Snowflake, and Power BI, the project delivers meaningful insights into monthly energy usage and identifies cost-saving opportunities for more efficient energy management.
The dataset, energy_consumption_data, contains records of electricity usage, cost, location, and other variables. The final output includes an interactive 2-page Power BI dashboard designed for decision-makers and stakeholders.

Tech Stack:
* Amazon S3 – Cloud storage for raw data
* AWS IAM – Role-based access configuration
* Snowflake – Cloud data warehouse for processing and transformation
* Power BI Desktop – Interactive data visualization and analysis
* SQL – For data cleaning, transformation, and aggregation

Project Workflow:
Step 1: AWS S3 Integration
* Uploaded energy_consumption_data.csv to Amazon S3 Bucket
* Configured IAM Role and set trust policies to allow Snowflake access
 Step 2: Snowflake Data Transformation
* Created integration object to link Snowflake with S3
* Executed SQL queries to:
    * Create a database and staging table
    * Load data from S3 to Snowflake
    * Perform data transformations (e.g., adding calculated columns, renaming fields, updating records)
Step 3: Power BI Dashboard Creation
* Connected Power BI to Snowflake and imported the transformed dataset
* Built a two-page dashboard for comprehensive analysis:

Dashboard Pages
Page 1: Monthly Usage Analysis
* Monthly Energy Consumption Trends
* Location-wise Consumption Breakdown
* Usage Distribution by Category
* Peak Usage Months
* Seasonal Comparison of Consumption
Page 2: Cost Saving Analysis
* Energy Cost Trends Over Time
* High Cost Locations
* Cost vs. Usage Ratio Visualization
* Opportunities for Cost Reduction (based on usage efficiency)

Key Insights:
* Identified months and locations with highest energy consumption
* Highlighted inefficient usage zones and potential savings
* Uncovered patterns across usage types and time frames to aid in cost control
* Enabled dynamic filtering to drill down into specific scenarios

Dataset Details:
* File Name: energy_consumption_data.csv
* Key Fields: Date, Location, Usage (kWh), Cost, Usage Category, Efficiency Score

 Learning Outcomes:
* Developed cloud-to-BI pipeline integrating AWS S3, Snowflake, and Power BI
* Improved expertise in SQL transformation and Power BI visual design
* Strengthened understanding of energy analytics and cost-efficiency metrics
* Gained experience in designing multi-page business reports for diverse audiences
