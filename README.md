![HOSPITAL IMAGE](https://github.com/user-attachments/assets/62c63755-1c11-4c2e-99a8-3de3a31b6fe1)


🏥 Hospital Transaction Power BI Dashboard

Power BI Status License Data Analysis

📊 Project Overview

This project involved the development of an interactive Power BI dashboard for City Hospital, aimed at delivering a centralized view of both financial and operational performance.

City Hospital, a well-established healthcare institution, encountered difficulties in making data-driven decisions due to limited visibility and the absence of unified reporting across financial and clinical operations.

As the Data Analyst on this project, my objective was to design a Power BI dashboard that enables management to:

Monitor key financial KPIs (Revenue, Expenses, Profit, Profit Margin)

Analyse performance trends over time

Identify top-performing specialties, doctors, and patients

Improve resource allocation and operational efficiency

🧩 Problem Statement

City Hospital did not have a centralized view of its financial performance, which limited its ability to detect trends, allocate resources effectively, and make informed decisions.

Goal: Convert raw hospital transaction data into meaningful, actionable dashboards that support strategic decision-making.

🧠 Steps Taken
1. Data Modeling

Created relationships between fact and dimension tables

Built a logical data model to support efficient querying and reporting

2. Data Cleaning & Integration

Detected and corrected missing, duplicate, and inconsistent data

Used Power Query to identify and manage null values

Standardized datasets to ensure accuracy before modeling

3. DAX Calculations

Developed calculated measures including:

Total Revenue

Total Expenses

Total Profit

Profit Margin (%)

Revenue by Procedure, Specialty, and Doctor

4. Dashboard Development

Built two interactive dashboards focusing on:

Financial Performance

Operational Analysis

📚 Data Dictionary

TransactionID — Unique transaction identifier
Date — Transaction date
RevenueAmount — Revenue from the transaction
ExpensesAmount — Expense associated with the transaction
Doctor_FirstName / Doctor_LastName — Attending doctor’s name
Doctor_Gender — Doctor’s gender
Specialty — Medical specialization
PatientID — Unique patient identifier
Patients_FirstName / LastName / Gender — Patient information
ProcedureName — Procedure performed
Category — Procedure category (e.g., Surgery, Radiology)
LocationID / City / State / Country / PostalCode — Hospital location details

📈 Key Performance Indicators (KPIs)

💰 Total Revenue, Expenses, and Profit

📊 Profit Margin (%)

🧑‍⚕️ Total Doctors

🧍‍♀️ Total Patients

⚕️ Revenue by Specialty

💼 Revenue by Procedure Category

📆 Revenue Trends Over Time

📉 Dashboard Insights
Dashboard 1 – Financial Performance

Revenue trends across time

Highest-performing specialties

Profit margin by procedure

Revenue and expenses by category

Dashboard 2 – Operational Analysis

Top revenue-generating doctors

Top 5 patients by revenue contribution

Doctor and patient distribution by specialty

Gender distribution of doctors and patients

Patient visit trends over time

🧩 Null Value Handling

Within Power Query:

Used View > Column Quality

Leveraged Valid / Error / Empty indicators to locate nulls

Filtered or replaced null values to maintain data integrity

🖥️ Technologies Used

Microsoft Power BI

Power Query

DAX (Data Analysis Expressions)

Data Modeling

Healthcare Financial Data

🏆 Outcomes & Recommendations

✅ Delivered a fully automated and interactive Power BI dashboard
✅ Enhanced visibility into financial and operational metrics
✅ Enabled management to:

Identify high-performing specialties

Optimize doctor allocation

Improve cost efficiency through profit monitoring
