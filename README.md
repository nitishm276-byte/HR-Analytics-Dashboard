# HR Analytics Dashboard | Power BI

An interactive HR Analytics dashboard built in Power BI to analyze employee attrition, demographics, and workforce trends using the IBM HR Employee Attrition dataset (1,470 employees, 24 attributes).

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-blue)
![Excel](https://img.shields.io/badge/Excel-Data%20Source-217346?logo=microsoft-excel&logoColor=white)

## 📊 Overview

This project transforms raw HR employee data into a single-page, decision-ready dashboard that lets HR/business stakeholders explore attrition drivers across departments, job roles, demographics, and work conditions — using KPI cards, charts, and interactive slicers.

## 🗂️ Dataset

- **Source file:** `Company_Data.xlsx`
- **Records:** 1,470 employees
- **Attributes:** 24 fields, including Attrition, Department, Job Role, Age, Gender, Marital Status, Education, Over Time, Monthly Income, Job Satisfaction, Work-Life Balance, Years at Company, and more.

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — data modeling, report design, interactivity
- **DAX** — custom measures (e.g., Total Employees, Total Attrition, Attrition Rate, Active Employees)
- **Excel** — source data review and preparation
- **Data Visualization** — KPI cards, bar/column charts, donut chart, area chart, funnel chart, pivot table

## 📈 Dashboard Features

| Visual | Insight it shows |
|---|---|
| KPI Cards | Total Employees, Total Attrition, Attrition Rate, Active Employees, Avg. Age, Avg. Monthly Income |
| Clustered Column Chart | Employee headcount by Age Group & Gender |
| Clustered Bar Chart | Attrition Rate by Job Role |
| Donut Chart | Attrition split by Department |
| Area Chart | Attrition trend across Age |
| Funnel Chart | Attrition by Education Field |
| Pivot Table | Job Satisfaction by Job Role |
| Slicers | Business Travel, Marital Status, Gender, Education (fully cross-filtered) |

## 🔑 Key Insights

- Overall attrition rate is **16.1%** (237 of 1,470 employees).
- **Sales** has the highest departmental attrition (20.6%) vs. **R&D**, the lowest (13.8%).
- **Sales Representatives** have the highest attrition of any job role, at **39.8%**.
- Employees who work **overtime** attrite at **30.5%**, nearly 3x the rate of those who don't (10.4%) — the single strongest attrition driver in the data.
- **Single** employees attrite more (25.5%) than married (12.5%) or divorced (10.1%) employees.
- Average employee age is 36.9 years; average monthly income is ~$6,503.

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/hr-analytics-dashboard.git
   ```
2. Open `Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft).
3. Use the slicers (Department, Gender, Marital Status, Education, Business Travel) to filter and explore attrition patterns interactively.

> Don't have Power BI Desktop? See the `screenshots/` folder for static views of the dashboard.

## 📁 Repository Structure

```
hr-analytics-dashboard/
├── Dashboard.pbix          # Power BI report file
├── Company_Data.xlsx       # Source dataset
├── screenshots/            # Dashboard preview images
└── README.md
```

## 👤 Author

**Nitish Mittal**
[LinkedIn](https://www.linkedin.com/in/nitish-mittal-bi) • [GitHub](https://github.com/nitishm276-byte)

---
*This project was built as part of a self-directed learning exercise to strengthen Power BI, DAX, and data storytelling skills.*
