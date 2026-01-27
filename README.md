# Customer Completeness Profile Dashboard (Power BI)

## 📌 Project Overview
This project focuses on analyzing and improving **customer profile data quality** using Power BI.  
The dashboard identifies missing, incomplete, or undefined customer information and provides clear insights to help stakeholders take corrective action.

The solution is designed to support **data governance, customer analytics, and operational decision-making**.

---

## 🎯 Business Problem
Incomplete customer profiles lead to:
- Poor customer communication
- Inaccurate reporting
- Ineffective business decisions

This dashboard helps answer:
- How many customer profiles are incomplete?
- Which fields are most frequently missing?
- Which companies have the highest data quality issues?
- How does data completeness vary by company, location, or template?

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
  - Power Query (Data Cleaning)
  - DAX (Measures & KPIs)
- **Microsoft Excel** (Source Data)
- **Data Modeling & Visualization**

---

## 📊 Dashboard Features
- **KPI Cards**
  - Total Profiles
  - Profiles with Missing Data
  - % of Incomplete Profiles

- **Visual Analysis**
  - Donut chart showing missing vs complete profiles
  - Bar chart: Top 5 companies with missing data
  - Field-wise missing data analysis

- **Table View**
  - Customer profiles with missing fields
  - Conditional formatting for Active/Inactive 

- **Interactive Slicers**
  - Company Name
  - Template ID
  - Location
  - Profile Status

---

## 📂 Dataset Description
The dataset contains customer profile information, including:
- Company Name
- Profile Status (Complete / Inactive)
- Contact Details
- Website
- About Section
- Profile Photo
- Location & Template Information

---

## 🔄 Data Cleaning Process
- Replaced blank values with **NULL**
- Standardized undefined values
- Created calculated columns and measures
- Filtered inactive and incomplete profiles
- Built data model optimized for reporting

---

## 🧮 Key DAX Measures
- Total Profiles
- Profiles with Missing Data
- Percentage of Incomplete Profiles
- Missing Field Count by Company

---

