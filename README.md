## 🚀 Portfolio Summary – Airline Loyalty Analytics Project ✨

This project presents a complete end-to-end data analytics workflow designed to replicate a real business intelligence environment. Using a combination of Python, SQL, and Power BI, I transformed raw airline loyalty data into a structured analytics model and delivered a fully interactive dashboard with meaningful business insights.

The process began by importing and cleaning the raw customer, flight, and calendar datasets in Python. I handled missing values, standardized formats, created new engineered features (such as customer status, membership duration, salary groups, CLV segments, and derived date fields), and prepared the data for analysis. Cleaned datasets were then loaded into a SQLite relational database, ensuring stronger data integrity, improved performance, and a scalable structure suitable for analytical querying.

With SQL, I explored the data, validated relationships, and confirmed the accuracy of flight activity, customer profiles, and loyalty behaviors before integrating the database into Power BI. Inside Power BI, I built a star-schema model, created analytical measures using DAX, established table relationships, and performed additional modeling and transformations to support more advanced reporting.

Finally, I designed a multi-page interactive dashboard focusing on:

Executive performance KPIs

Customer segmentation (demographic, behavioral, value-based)

Churn and retention insights

Loyalty engagement and points behavior

Membership duration and CLV patterns

This project showcases my ability to work across the full analytics stack—data cleaning, feature engineering, database modeling, SQL querying, DAX development, and dashboard design—to produce insights that support strategic business decisions.

It demonstrates practical experience with modern data tools and mirrors the expectations of real-world data analyst and BI analyst roles.





# 🧹 1. Data Cleaning, Database creation and Data Modeling & DAX 

Firstly, I started with raw Excel files containing customer details, flight activity, and a calendar table.
In Python (Jupyter Notebook), I:

-Cleaned the datasets
-Fixed missing values
-Standardised columns

Created new useful fields such as Customer Status, Membership Duration, Salary Groups, CLV Segments and more. 

Secondly, To make the project more realistic and scalable. I loaded all cleaned datasets into a **SQLite relational database**.  

-Structured the tables as a relational model
-Ran SQL queries to validate the data and explore patterns

This allowed me to use SQL for exploration, validation, and structured querying before connecting to Power BI.

Finally, Inside Power BI, I Connected to the SQL database

**Built a data model (relationships between customer, flights, and calendar)**

Created business measures such as:

-Customer Count
-Churn Rate
-Total Flights
-Average Flights per Customer
-Average CLV
-Points Accumulated & Redeemed and more.

I created business calculations (DAX measures) for customer counts, churn rate, total flights, CLV averages, points behavior, and more — preparing the model for meaningful dashboards.


📁 Raw data: [Raw Data](https://github.com/Ali-Sikder/Airline-Loyalty-Analytics/blob/main/Raw%20Data)
📁 Notebook: `/notebooks/01_data_cleaning_and_sql_import.ipynb`
📁 SQL scripts: `/sql/airline_loyalty_analysis.sql`  
📁 Database file: `airline_loyalty.db`
📁 Power BI file: `/powerbi/Airline_Loyalty_Report.pbix`





# 📈 4. Dashboard & Insights (Power BI)

### 🔹 Page 1 — Flight Detail 
<img width="1094" height="613" alt="image" src="https://github.com/user-attachments/assets/4d6a741d-10c3-4fd6-a56f-fe9eac87e5f0" />


The Flight Details dashboard provides a clear overview of how customers engage with the airline’s loyalty program, helping managers quickly understand flight activity, retention, and customer behaviour. The top section highlights key metrics such as total customers, active vs cancelled customers, average flights per customer, total points redeemed, and total flights. These KPIs allow decision-makers to monitor program performance at a glance.

The dashboard then visualizes monthly patterns, including total flights and total points accumulated. These charts reveal seasonal travel trends and help the airline identify peak months, forecast demand, and plan staffing or promotional activities more effectively. Additional visuals compare flight behaviour across customer groups—such as by loyalty card tier, salary group, and customer status—making it easy to identify which segments fly more frequently or redeem more rewards. This supports personalised marketing, loyalty strategy improvements, and targeted incentives.

Together, these insights help managers strengthen customer retention, refine loyalty benefits, optimize operational planning, and better understand which customer groups contribute most to travel activity. The dashboard transforms raw data into actionable information, enabling smarter decisions that enhance customer engagement and drive the airline’s overall performance.

### 🔹 Page 2 — Customer Segmentation
<img width="1090" height="611" alt="image" src="https://github.com/user-attachments/assets/a0a6b70e-30ef-47e3-aa77-b4d6b244cad3" />

The Customer Segmentation dashboard helps the airline understand who its customers are and how different groups behave within the loyalty program. By breaking the population into segments such as lifetime value, education, gender, loyalty card tier, and membership duration, managers can easily identify which customer groups generate the most value and which may require better engagement strategies. The first set of visuals highlights how Customer Lifetime Value (CLV) differs across segments and how many points each group accumulates or redeems. This allows the business to recognize its most profitable customers and ensure marketing efforts are directed toward retaining them.

The dashboard also shows patterns in education level, enrollment type, gender distribution, and churn rate across customer categories. These insights reveal behavioural differences—for example, whether certain groups are more loyal, fly more often, or are at higher risk of cancelling their membership. This is especially useful for designing targeted promotions or onboarding improvements. The membership duration analysis further helps the airline understand how value changes over time and whether newer members behave differently from long-term ones.

Overall, this dashboard supports smarter decision-making by giving a complete picture of customer diversity and behaviour. Managers can use these insights to refine loyalty tiers, personalise marketing, reduce churn, and improve customer lifetime value. It transforms segmentation from a simple demographic breakdown into actionable strategy.

📁 Dashboard screenshots: `/docs/`










# 🎯 6. Key Business Insights
This project successfully transformed a raw airline loyalty dataset into a complete analytical ecosystem using Python, SQL, and Power BI. The two dashboards—Flight Operations and Customer Segmentation—work together to give the airline a clear, data-driven understanding of both customer behaviour and operational performance.

The Flight Details dashboard highlights monthly flight activity, points accumulation patterns, customer status distribution, and overall loyalty program performance. These insights help operations and marketing teams identify peak travel periods, understand program engagement, and measure key performance indicators such as churn rate, total flights, and points redeemed.

The Customer Segmentation dashboard adds a deeper layer of intelligence by profiling customers based on value, demographics, loyalty tiers, education, membership duration, and enrolment type. These insights reveal which customer groups generate the most revenue, which segments are at higher risk of churn, and how different types of members behave across the loyalty lifecycle.

Together, both dashboards provide a 360° view of the loyalty program—combining operational metrics with customer-level insights. This empowers the airline to:

-Allocate resources based on real flight behaviour
-Personalise marketing for high-value segments
-Detect at-risk customers earlier
-Strengthen engagement strategies
-Improve long-term customer loyalty and revenue

This project demonstrates the full data pipeline—cleaning, modelling, analysis, and visualization—resulting in a powerful decision-support tool that helps businesses improve both customer satisfaction and operational performance.





# 🤝 7. How to Explore This Project
Use this homepage as your guide. Each section links directly to the work:

- Cleaned Data → `/data/processed/`  
- SQL Scripts → `/sql/`  
- Python Notebook → `/notebooks/`  
- Power BI Dashboard → `/powerbi/`  
- Screenshots → `/docs/`
