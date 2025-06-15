# POWER-BI-PROJECTS
This repository contains a comprehensive Power BI project focused on analyzing insurance data using **Microsoft SQL Server** and **Power BI Desktop**. The project walks through real-world steps of preparing, visualizing, and publishing a professional dashboard — ideal for data analyst and BI developer portfolios.

---

##  Project Contents

| File                               | Description                                                      |
|-------------------------------     |------------------------------------------------------------------|
| `insurance_dashboard.pbix`         | Main Power BI report with visualizations and insights            |
| `sql_source_data.CSV`              | csv data uploaded to SQL Server for simulation                   |
| `Insurance+Customer+Feedback.xlsx` | Excel file used directly in Power BI for sentiment analysis      |
| `README.md`                        | Project documentation                                            |

---

##  Key Concepts Covered

This project is part of a practical learning series, where the following skills were applied and demonstrated:

###  Data Preparation & Modeling
- Installing and setting up **Microsoft SQL Server**
- Importing Excel data into SQL Server
- Connecting SQL Server and Excel files to Power BI
- Data profiling and transformation using **Power Query**

###  Power BI Visualizations
- **Slicers, Card Visuals, Multi-row Cards**
- **Ribbon, Bar, Line, and Donut Charts**
- **Matrix Visual**
- **Custom visuals** like **Word Cloud** from AppSource
- Creating **Table View** and applying **Drillthrough Filters**

###  Advanced Features
- **Sentiment Analysis** using Text Analytics in Power Query
- **Row-Level Security (RLS)** setup and testing
- **Scheduled Data Refresh** using Personal Mode Gateway
- Understanding the difference between **Reports vs Dashboards**

---

##  Report Overview

### **Page 1: Overview Dashboard**
- Company name text box
- High-level KPIs using card visuals
- Charts (bar, ribbon, donut) for categorical analysis

### **Page 2: Detailed Table View**
- Tabular layout of records
- Drillthrough filters enabled

### **Page 3: Sentiment Analysis-Feedback**
- Feedback visualized using a **Word Cloud**
- Custom visuals from AppSource
- Showcasing feedback trends and sentiment distribution

---

##  Deployment Steps

1. Open `Insurance Dashboard.pbix` in **Power BI Desktop**.
2. If file paths break, use:
   - `Transform Data > Source` to update Excel paths
   - `Data source settings` to reconnect SQL Server (enter server and database name)
3. Refresh the data.
4. Publish to **Power BI Service**.
5. Use **Personal Mode Gateway** for scheduled refresh (configured in Power BI Service).

---

##  Note on Data

- This dataset is **dummy insurance data** used strictly for learning purposes.
