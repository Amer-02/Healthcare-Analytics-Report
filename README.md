# 🏥 Healthcare Analytics Dashboard – Power BI

This project presents an interactive Power BI dashboard that analyzes healthcare waitlist data from 2018 to 2021. It focuses on medical care trends across inpatient, outpatient, and day case treatments. The goal is to visualize pressures on the healthcare system, especially before and after the COVID-19 pandemic (using interactive filters), and to support insights for capacity planning and resource allocation.

It involves:

- 📊 **Data Cleaning** in **Excel**
- 📈 **Interactive Dashboards** built with **Power BI**

---

## 📌 Key Features

- Year-over-year comparison of waitlist volumes (2018–2021)
- Interactive filtering by:
  - **Treatment type**: Inpatient, Outpatient, Day Case
  - **Age groups**
  - **Wait time bands**
  - **Specialties**
- Custom KPIs and DAX measures

---

## 🛠 Tools & Technologies Used

- Power BI - **Power BI Desktop** (data modeling, DAX, visualization)
           - **Power Query** (data cleaning and transformation)
- Excel (For minor data review)

---

## 📁 Files

| File | Description |
|------|-------------|
| `IN_WL 2018.csv`, `IN_WL 2019.csv`, `IN_WL 2020.csv`, `IN_WL 2021.csv` | Inpatient waiting list data |
| `Op_WL 2018.csv`, `Op_WL 2019.csv`, `Op_WL 2020.csv`, `Op_WL 2021.csv` | Outpatient waiting list data |
| `Mapping_Specialty.csv` | Mapping for treatment specialties |
| `Healthcare Analytics Project.pbix` | Power BI dashboard file |

All data has been cleaned and combined (within Power BI) to allow for cross-year comparisons and visual exploration.

---

## 📈 Sample Dashboard
![Screenshot 2025-05-27 180105](https://github.com/user-attachments/assets/b6068ee3-53ed-4b4f-86a1-d69a248c9ff6)

---

## 🔍 Insights Uncovered

- Tracks waitlist trends from 2018 to 2021
- Breaks down by treatment type: inpatient, outpatient, day case
- Shifts in wait times for different age groups and specialties
- Shows demand by medical specialty
- Groups patients by age categories
- Includes interactive filters for custom exploration
- Compares pre- and post-COVID-19 waitlist impacts


**✨ Although not originally designed with COVID-19 in mind, the data spans both pre- and post-pandemic years, making it useful for analyzing the impact of COVID-19 on healthcare backlogs.**

---

## 📌 Possible Extensions

- Add drill-through pages for specialty- or region-specific insights
- Publish to Power BI Service for web-based access

---
