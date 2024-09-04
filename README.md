AtliQ Hardware Power BI Dashboard
Project Overview
AtliQ Hardware manufactures and sells hardware like PCs, mice, printers, and more to companies worldwide, including Croma, Amazon, Neptune, Staples, and Walmart. AtliQ's customers fall into two categories: Physical Stores and E-commerce platforms.

Problem Statement
AtliQ Hardware is currently struggling to achieve good business results in Latin America. Previous decisions were made based on surveys and intuition, which proved insufficient. With an increase in data availability, AtliQ Hardware has decided to leverage data analytics for more accurate and informed decision-making.

Objective
The objective of this project is to create a dynamic Power BI dashboard to provide actionable insights to AtliQ Hardware's management team. The dashboard will cover finance, sales, marketing, supply chain, and executive views to aid in strategic decision-making.

Tools & Technologies
MySQL: Database management and querying.
Power BI: Data visualization and dashboard creation.
Power BI Service: For sharing and collaboration.
DAX Studio: Advanced DAX calculations and performance tuning.
Project Execution Steps
Step 1: Data Loading
Data was loaded into the MySQL database and then connected to Power BI for further processing.

Step 2: Database Relationships
Default database relationships created by Power BI were reviewed and deleted. Necessary dimension tables were created in Power Query.

Step 3: Data Validation
Data was validated using Power BI tables and matched against the original data to ensure accuracy.

Step 4: Data Transformation
A Last Sales Month Reference table was created to dynamically update after every sale.

Step 5: Calculated Columns
Calculated columns such as fiscal_year were created in Power Query, and tables were merged as required.

Step 6: Data Modeling
A star schema was used for data modeling, where all dimension tables were connected to fact tables.

Step 7: DAX Formulas
Over 40 DAX formulas were created for calculated columns. These were verified against data in MySQL or Excel.

Step 8: Report Optimization
The report was optimized to reduce file size, making it easier to share and access.

Dashboard Views
1. Home Page
The home page includes navigation to all other views and a summary of each page, allowing users to quickly access the reports they need.

2. Finance View
This view displays Profit & Loss statements, performance of top and bottom products and customers, and year-on-year P&L comparisons. A button was added to show Net Sales performance versus the previous year and target.

3. Sales View
This view allows the sales team to drill down into the performance of each product and customer in individual regions, providing an in-depth analysis of sales performance.

4. Marketing View
Includes key financial metrics such as Gross Margin %, Net Profit %, and Operational Expenses to help decide marketing budgets and identify potential customers and markets.

5. Supply Chain View
Provides insights into the reliability and accuracy of supply chain performance. Historical data helps in making informed decisions about inventory management and delivery times.

6. Executive View
A consolidated report with key metrics like NS, RC%, GM%, NP%, Forecast Accuracy %, Market Share, top-selling products, and top customers. This view is designed for senior stakeholders who need a high-level overview.

Learnings
This project provided an opportunity to deepen my understanding of Power BI, data modeling, dashboard creation, and various business metrics. I also gained experience in working with Profit & Loss statements, sales comparisons, and forecasting.
