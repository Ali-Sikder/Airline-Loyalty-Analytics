## 1. 🚀 Portfolio Summary – Airline Loyalty Analytics Project ✨

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






## 2. 🧹 Data Cleaning, SQL Database Creation & Power BI Data Modeling

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

### 📁 Project Files  
- Raw data: [Raw Data Folder](https://github.com/Ali-Sikder/Airline-Loyalty-Analytics/blob/main/Raw%20Data)  
- Notebook: `/notebooks/01_data_cleaning_and_sql_import.ipynb`  
- SQL scripts: `/sql/airline_loyalty_analysis.sql`  
- Database file: `airline_loyalty.db`  
- Power BI report: `/powerbi/Airline_Loyalty_Report.pbix`





# 📈 3. Dashboard & Insights (Power BI)

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










# 🎯 4. Key Business Insights and conclusion
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





# 🤝 5. How to Explore This Project
Use this homepage as your guide. Each section links directly to the work:

- Cleaned Data → `/data/processed/`  
- SQL Scripts → `/sql/`  
- Python Notebook → `/notebooks/`  
- Power BI Dashboard → `/powerbi/`  
- Screenshots → `/docs/`
