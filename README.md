# SecureCheck: Python-SQL Digital Ledger for Police Check Post Logs
## 🚀 Project Overview

Police check posts often rely on manual logs and inefficient databases, slowing down operations. SecureCheck provides:

- Real-time vehicle and personnel logging.
- Automated alerts for flagged vehicles.
- Streamlit dashboard for trend analysis and officer reporting.
- SQL-based queries for quick lookups and analytics.
- Centralized database for multi-location check posts.
## 🛠️ Features

- **Real-time Monitoring:** Log and track vehicles, drivers, and violations instantly.
- **Automated Alerts:** Flag suspicious vehicles based on SQL queries.
- **Data Analytics:** Analyze violations, stop durations, and demographic trends.
- **Search & Filters:** Quickly lookup vehicles, drivers, violations, and times.
- **Performance Metrics:** Fast query execution, accurate data, and real-time updates.
- ## 🗂️ Database & SQL

**Tables Example:**  
- Vehicle Logs
- Driver Details
- Violations
- Officer Reports
## 💻 Python & Streamlit Implementation

**Data Processing Steps:**  
1. Remove columns with only missing values.  
2. Handle NAN values for clean data.  
3. Insert processed data into SQL database using Python & SQLAlchemy.  

**Streamlit Dashboard Features:**  
- Display vehicle logs, violations, and officer reports.  
- SQL-based search filters for quick lookups.  
- Analytics charts for trends (high-risk vehicles, violation statistics).  
