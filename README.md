## 🚀 Project Overview
This project analyses how airline customers behave in a loyalty program.

I used Python, SQL, and Power BI to clean real customer and flight data, build a structured database, and create interactive dashboards that reveal insights about loyalty, customer value, and churn.

This portfolio gives a simple explanation of what I did in each stage.
Click the links under each section to explore the actual files in the project.

---

# 🧹 1. Data Cleaning & Preparation (Python)

I started with raw Excel files containing customer details, flight activity, and a calendar table.
In Python (Jupyter Notebook), I:

Cleaned the datasets

Fixed missing values

Standardised columns

Created new useful fields such as Customer Status, Membership Duration, Salary Groups & CLV Segments

Exported clean datasets for next steps

📁 Raw data: [Raw Data](https://github.com/Ali-Sikder/Airline-Loyalty-Analytics/blob/main/Raw%20Data)

📁 Notebook: `/notebooks/01_data_cleaning_and_sql_import.ipynb`

---

# 🗄️ 2. Database Creation (SQL / SQLite)

To make the project more realistic and scalable (like real analytics teams). 

I loaded all cleaned datasets into a **SQLite relational database**.  

Structured the tables as a relational model

Ran SQL queries to validate the data and explore patterns

This allowed me to use SQL for exploration, validation, and structured querying before connecting to Power BI.

📁 SQL scripts: `/sql/airline_loyalty_analysis.sql`  
📁 Database file: `airline_loyalty.db`

---

# 📊 3. Data Modeling & DAX (Power BI)

Inside Power BI, I:

Connected to the SQL database

**Built a data model (relationships between customer, flights, and calendar)**

Created business measures such as:

Customer Count

Churn Rate

Total Flights

Average Flights per Customer

Average CLV

Points Accumulated & Redeemed

I created business calculations (DAX measures) for customer counts, churn rate, total flights, CLV averages, points behavior, and more — preparing the model for meaningful dashboards.

📁 Power BI file: `/powerbi/Airline_Loyalty_Report.pbix`

---

# 📈 4. Dashboard & Insights (Power BI)

### 🔹 Page 1 — Executive Summary
- Customer count  
- Active vs Cancelled  
- Churn rate  
- Total flights  
- Avg distance per flight  
- Points accumulated & redeemed  
- Monthly flight and points trends  

### 🔹 Page 2 — Customer Segmentation
- Customer profiles by gender, education, salary  
- Loyalty card usage  
- Customer lifetime value patterns  
- Membership duration behavior  
- Flight engagement  
- Redemption efficiency  
- Churn and retention indicators  

📁 Dashboard screenshots: `/docs/`

---

# 🔍 5. What I Learned / Demonstrated

This project shows my ability to work across the full analytics pipeline:

- Clean and structure messy data  
- Build a relational database  
- Work with SQL for analysis  
- Create a strong data model  
- Build DAX measures  
- Design business-ready dashboards  
- Communicate insights clearly  

It reflects real workflows in **Data Analyst and BI Analyst roles**.


---

# 🎯 6. Key Business Insights
- High-value customers contribute significantly more to revenue.  
- Some segments show higher churn risk.  
- Points redemption varies widely across customer groups.  
- Membership duration influences customer lifetime value.  
- Loyalty card tier strongly affects flight behavior.  

---

# 🤝 7. How to Explore This Project
Use this homepage as your guide. Each section links directly to the work:

- Cleaned Data → `/data/processed/`  
- SQL Scripts → `/sql/`  
- Python Notebook → `/notebooks/`  
- Power BI Dashboard → `/powerbi/`  
- Screenshots → `/docs/`
