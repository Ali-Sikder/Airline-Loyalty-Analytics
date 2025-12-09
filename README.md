# 1. Portfolio Summary – Airline Loyalty Analytics Project 

This project demonstrates a complete end-to-end analytics workflow designed to model a real business intelligence environment. Using **Python**, **SQL (SQLite)**, and **Power BI**, I transformed raw airline loyalty data into a structured analytical model and developed an interactive dashboard that highlights key business insights.

I began by importing and cleaning the raw customer, flight, and calendar datasets in **Python (Pandas)**. This included handling missing values, standardising formats, and engineering new features such as **Customer Status**, **Membership Duration**, **Salary Groups**, **CLV Segments**, and various date-based classifications.  
Once cleaned, the datasets were loaded into a **SQLite relational database**, providing stronger data integrity and a scalable foundation for analytical queries.

Using **SQL**, I explored customer behaviour, validated relationships between tables, and ensured the accuracy of flight activity and loyalty patterns. The database was then connected to **Power BI**, where I built a star-schema model, defined analytical measures using **DAX**, and created relationships to support deeper reporting and trend analysis.

The final dashboard focused on several key analytical areas:

- **Executive KPI performance**  
- **Customer segmentation** (demographic, behavioural, and value-based)  
- **Churn and retention analysis**  
- **Loyalty engagement and points behaviour**  
- **Membership duration and CLV patterns**  

This project highlights my ability to work across the full data analytics spectrum—from data cleaning and feature engineering to database design, SQL querying, DAX development, and dashboard storytelling.  
It reflects real-world expectations for **Data Analyst** and **BI Analyst** roles and demonstrates my capability to deliver meaningful insights that support strategic business decisions.






# 2. Data Cleaning, SQL Database Creation & Power BI Data Modeling

This project followed a complete end-to-end data analysis workflow across Python, SQL, and Power BI.

I began by cleaning the raw Excel datasets (customers, flights, and calendar) using **Python (Pandas in Jupyter Notebook)**. This included handling missing values, standardising columns, and engineering new fields such as **Customer Status**, **Membership Duration**, **Salary Groups**, **CLV Segments**, and other useful analytical attributes.

To make the project more structured and realistic, all cleaned datasets were loaded into a **SQLite relational database**. I designed the tables according to relational principles, created keys, and ran **SQL queries** to validate data quality and explore patterns before building the BI model.

Inside **Power BI**, I connected directly to the SQLite database and created a robust **data model** linking customers, flights, and calendar tables. I then built key **DAX measures** used for business insights, including:

- Customer Count  
- Churn Rate  
- Total Flights  
- Average Flights per Customer  
- Average CLV  
- Points Accumulated & Redeemed  

These metrics formed the foundation for an interactive dashboard that visualises customer behaviour, loyalty performance, and business trends.

### Project Files  
- Raw data: [Raw Data Folder](https://github.com/Ali-Sikder/Airline-Loyalty-Analytics/blob/main/Raw%20Data)  
- Notebook: `/notebooks/01_data_cleaning_and_sql_import.ipynb`  
- SQL scripts: `/sql/airline_loyalty_analysis.sql`  
- Database file: `airline_loyalty.db`  
- Power BI report: `/powerbi/Airline_Loyalty_Report.pbix`





# 3. Dashboard & Insights (Power BI)

### 🔹 Page 1 — Flight Detail 

A fast, visual overview of flight performance and loyalty program activity.

### What This Dashboard Shows

Overall customer activity: Total customers, active vs. cancelled members, churn rate

Program engagement: Total flights flown, points accumulated & redeemed

Monthly trends: Flights and points activity by month

Customer behaviour patterns:
- Avg flights per customer
- Avg distance per flight
- Flights by loyalty card type
- Flights by income group or customer status

<brk>
<brk>


<img width="1094" height="613" alt="image" src="https://github.com/user-attachments/assets/4d6a741d-10c3-4fd6-a56f-fe9eac87e5f0" />

<brk>
<brk>

### Why This Dashboard Matters

Quickly identifies seasonal flight trends

Helps spot engagement drop-offs and churn risk

Shows which loyalty tiers contribute the most flights

Supports decisions around:
- Staffing & resource planning
- Flight scheduling
- Loyalty rewards optimization
- Customer engagement strategies

### 🔹 Page 2 — Customer Segmentation

A deeper look into who the customers are and how different groups behave.

### What This Dashboard Shows

Customer demographics: Gender, education, income groups

Customer value tiers: High/medium/low CLV segments

Loyalty card distribution: Star, Nova, Aurora

Membership behavior:
- Average CLV by enrolment type
- CLV by membership duration
- Customer count by lifetime value
- Points redemption rate by card type

<brk>
<brk>

<img width="1090" height="611" alt="image" src="https://github.com/user-attachments/assets/a0a6b70e-30ef-47e3-aa77-b4d6b244cad3" />

<brk>
<brk>

### Why This Dashboard Matters

Reveals which segments bring the most value

Highlights which groups are more loyal or at risk

Helps build targeted marketing & retention campaigns

Supports decisions around:
- Loyalty benefits
- Customer retention strategies
- Personalized promotions
- Program redesign & tier optimization

 Dashboard screenshots: `/docs/`











# Key Business Insights & Conclusion

This project transformed a raw airline loyalty dataset into a complete analytical ecosystem using **Python**, **SQL**, and **Power BI**. The two main dashboards—**Flight Operations** and **Customer Segmentation**—work together to give the airline a comprehensive, data-driven view of customer behaviour and operational performance.

###  Flight Operations Insights  
The Flight Details dashboard uncovers trends in monthly flight activity, points accumulation, loyalty status distribution, and overall program performance.  
It enables the business to understand:

- Seasonal and monthly patterns in flight activity  
- How customers earn and redeem loyalty points  
- Engagement levels of different loyalty tiers  
- Key performance indicators such as **churn rate**, **total flights**, and **points redeemed**

These insights support operational planning, marketing decisions, and loyalty strategy optimisation.

###  Customer Segmentation Insights  
The Customer Segmentation dashboard provides deeper intelligence by profiling customers based on:

- Value and spending behaviour  
- Demographics and education  
- Loyalty tier and membership age  
- Enrolment type and activity patterns  

This helps identify high-value segments, detect at-risk customers, and understand which groups contribute most to long-term loyalty and revenue.

###  Combined Impact  
Together, both dashboards offer a **360° view of the loyalty program**, combining operational metrics with customer-level insights.  
This empowers the airline to:

- Allocate resources based on real flight behaviour  
- Personalise marketing for high-value segments  
- Predict churn and intervene earlier  
- Strengthen engagement and retention strategies  
- Improve overall customer satisfaction and revenue performance  

###  Final Summary  
This project demonstrates the full analytics pipeline—**data cleaning → database modelling → SQL analysis → Power BI reporting**—resulting in a powerful decision-support tool.  
It reflects real-world expectations for **Data Analyst** and **BI Analyst** roles by translating raw data into clear, actionable business insights.





#  5. How to Explore This Project
Use this homepage as your guide. Each section links directly to the work:

- Cleaned Data → `/data/processed/`  
- SQL Scripts → `/sql/`  
- Python Notebook → `/notebooks/`  
- Power BI Dashboard → `/powerbi/`  
- Screenshots → `/docs/`
