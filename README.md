# n8n-data-analysis-workflow
# Automated KPI & Employee Insights with n8n

This repository contains an n8n workflow for automating employee data analysis and reporting. The workflow ingests data from Google Sheets, computes KPIs, generates visualizations using QuickChart, and delivers an HTML report via Gmail.

---

## Key Features

### Data Ingestion
- Employee data is pulled from Google Sheets into n8n.

### Data Cleaning & Transformation
- Handles missing values such as salaries.  
- Normalizes and validates performance scores.  
- Categorizes salary values into ranges for further analysis.  

### KPI Calculations
- Average Salary  
- Average Performance Score  
- Count of Remote Employees  

### Data Visualization
- Bar chart of employee performance scores  
- Donut chart of salary ranges  

### Automated Reporting
- Generates an HTML report summarizing KPIs and visual insights  
- Embeds a link to the source Google Sheet  
- Sends the report automatically through Gmail  

---

## Tech Stack

- **n8n** – Workflow automation and orchestration  
- **Google Sheets** – Source system for employee data  
- **QuickChart.io** – API-based chart generation  
- **JavaScript (n8n Code Nodes)** – Data processing and HTML report creation  
- **Gmail Node** – Automated distribution of reports  

---

## Example Output

### KPI Summary

| Metric                   | Value   |
|---------------------------|---------|
| Average Salary            | 65,000+ |
| Average Performance Score | 6.4     |
| Remote Employees          | 7       |

### Charts Included in Report
- Performance scores by employee (bar chart)  
- Salary distribution by ranges (donut chart)  

---

### Repository Structure
n8n-employee-insights/
├── workflow.json
├── sample-report.html
├── README.md
└── assets/

---

Workflow Screenshot
Report 

## Repository Structure

