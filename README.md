# 👥 Employee Performance & Workforce Analytics

## 📌 Project Overview
This project focuses on **Workforce Analytics and Performance Management** using an organization's HR dataset. The goal is to analyze department-wise spending, employee productivity, geographical distribution, and financial metrics like revenue contribution versus operational costs. This repository contains the raw master data, pre-calculated pivot models, and visual dashboard layouts.

## 📊 Key Insights & Analytics Covered
The project transforms raw employee records into actionable HR and business insights:

* **Department & Cost Analysis:** Tracking total salary spending and overall operational costs across various corporate functions (**Operations, Support, Accounts, Sales**).
* **Revenue Generation Mapping:** Pinpointing the exact revenue contribution driven by the Sales team across different regional branches.
* **Geographical Distribution:** Workforce and budget allocation trends across key corporate hubs (**Bangalore, Mumbai, and Pune**).
* **Productivity Tracking:** Monitoring operational workload by evaluating the volume of tasks assigned to individual team members.

---

## 🗂️ Dataset Information & Data Dictionary

The project utilizes data structured across a master repository containing standard workforce tracking metrics:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| **Emp Id** | Integer | Unique identification number assigned to each employee |
| **Name** | String | Full name of the employee |
| **Department** | String | Allocated functional department (Operations, Sales, Support, Accounts) |
| **Salary** | Integer | Base monthly or annual salary compensation of the employee |
| **Location** | String | Corporate branch city (Bangalore, Mumbai, Pune) |
| **Date of Joining** | Date | Official date the employee entered the organization |
| **Team** | String | Combined metric mapped as `Department + Location` for operational tracking |
| **Revenue Contribution**| Integer | Direct monetary value brought into the company (Specific to the Sales team) |
| **Cost** | Float | Total operational/resource cost incurred by the company for that employee |
| **Tasks Assigned** | Integer | Metric tracking current individual workload/tasks allocated |

### 📈 Dataset Summary
* **Total Workforce Monitored:** ~160+ active corporate employee records.
* **Financial Scale:** Captures **$2.48M+** in base salaries and over **$9.80M** in tracked revenue contributions, predominantly led by the Bangalore Sales division.

---

## 🛠️ Tools & Technologies Used
* **Microsoft Excel / Google Sheets:** Used as the primary data storage engine, utilizing complex **Pivot Tables** for localized data roll-ups, conditional formatting, and aggregations.
* **Data Visualization:** Structured reports summarizing organizational structures through layout designs (`employee_data.png`).

## 📂 Project Repository Structure
* `employee_data.xlsx - Master Data.csv`: Cleaned core data containing granular employee details.
* `employee_data.xlsx - pivot table.csv`: Summarized operational matrices including `Sum of Salary`, `Sum of Revenue Contribution`, and `Sum of Cost`.
* `employee_data.png`: Image snapshot displaying the data management layout or visual metrics representation.
