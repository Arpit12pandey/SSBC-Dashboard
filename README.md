# Power BI Project – Seven Sages Brewing Company

## Overview
As part of Udacity’s **Nanodegree Program in Data Analysis and Visualization with Microsoft Power BI**, this project focused on data preparation, modeling, and visualization within Power BI.

The objective was to design a comprehensive report for a fictional company, **Seven Sages Brewing Company**, to help the CFO analyze beer sales and profitability metrics across the business.

Using the provided datasets, I built a well-structured data model and recreated an executive-style report that delivers clear insights into top-performing products and key financial drivers. The project emphasized best practices in Power BI, including:

- Data transformation using Power Query
- Establishing proper relationships
- Implementing DAX measures for profitability analysis

---

## ETL Process

### Data Cleanup
- Promoted first rows to headers where necessary
- Reviewed and corrected data types for all fields
- Renamed ambiguous queries for easier identification
- Renamed unclear columns for better usability
- Removed all blank rows
- Deleted unnecessary columns
- Corrected obvious typos impacting analysis

---

## Combining Data

- Merged dimension tables using 1-to-1 relationships
- Combined **CFO Metrics Tracker** and **SSBC Product Offerings** into a unified `Product` table
- Appended monthly files from the `Monthly Sales Logs` folder into a consolidated `Sales` table

---

## Date Table Creation

A dynamic date table was created with the following properties:
- Start: Beginning of the calendar year of the earliest sales record
- End: End of the calendar year of the latest sales record
- Columns included:
  - Calendar Month Number and Name
  - Calendar Year
  - Fiscal Period
  - Fiscal Year
  - Fiscal Quarter (e.g., Q2-FY2020)

> **Note:** Seven Sages’ fiscal year begins on **October 1st** and ends on **September 30th**

---
## Data Model:
<img width="1403" height="718" alt="image" src="https://github.com/user-attachments/assets/2030c919-9fff-418b-aa3e-11655778fa2e" />

---


## Measures (DAX)

- `Total Sales (USD)`
- `Cost of Sales (USD)`
- `Gross Profit Margin (%)`
- `Sales (CAD)`
- `Unit Sales by Product (% / USD)`
- `Gross Profit by Product (% / USD)`

---

## Key Learnings

- Practical application of ETL and data modeling in Power BI
- Use of DAX for meaningful financial insights
- Efficient report recreation based on a business-focused layout

---
## Report 
<img width="1363" height="767" alt="image" src="https://github.com/user-attachments/assets/6763d024-f5be-461d-984d-e6bcbab6dbae" />
<img width="946" height="577" alt="image" src="https://github.com/user-attachments/assets/daf1d8c6-7334-4fac-af28-c7dd7a53cc17" />

---



