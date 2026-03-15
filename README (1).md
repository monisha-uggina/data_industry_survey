# 📊 Data Professional Survey Breakdown — Power BI Dashboard

An interactive Power BI dashboard built to visualize and analyze survey responses from data professionals worldwide. This project explores salary trends, programming language preferences, career entry difficulty, and job satisfaction across various data roles.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Data_Industry_Survey_Analysis.pbix` | Main Power BI report file |

---

## 📌 Dashboard Overview

The dashboard consists of a single, fully interactive page with the following visuals:

| Visual | Type | Description |
|--------|------|-------------|
| **Average Salary by Job Title** | Bar Chart | Compares average salaries across data roles (Data Scientist, Data Engineer, etc.) |
| **Favourite Programming Language** | Column Chart | Breakdown of preferred languages (Python, R, SQL, etc.) by count of voters |
| **Country of Survey Takers** | Treemap | Geographic distribution of respondents |
| **Difficulty Breaking into Data** | Donut Chart | How hard respondents found it to enter the data field |
| **Happiness with Salary** | Gauge | Average satisfaction score for compensation |
| **Happiness with Work/Life Balance** | Gauge | Average satisfaction score for work-life balance |
| **Count of Survey Takers** | KPI Card | Total number of respondents |
| **Average Age** | KPI Card | Mean age of survey participants |

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** (v2026.02)
- **Power Query** — data cleaning and transformation
  - Removed irrelevant columns (Browser, OS, City, Referrer)
  - Simplified job title and programming language categories
  - Derived average salary from salary range columns
- **DAX** — calculated measures for averages and counts
- **Data Visualization** — gauge, treemap, donut, bar, column, and card visuals

---

## 📊 Dataset

The dataset is based on a real-world survey of data professionals, collected by [Alex Freberg (Alex the Analyst)](https://www.youtube.com/@AlexTheAnalyst). It contains **617 records** across **28 columns**, covering:

- Job title / current role
- Annual salary range
- Country of residence
- Favourite programming language
- Difficulty breaking into the data field
- Job satisfaction (salary & work/life balance)
- Age

---

## 🔍 Key Insights

- **Data Scientists** earn the highest average salaries among all data roles
- **Python** is the most popular programming language among data professionals
- The **United States** has the highest average salaries, while **India** has the lowest
- Most respondents found breaking into data **neither easy nor very difficult**
- Work/life balance satisfaction scores are generally higher than salary satisfaction

---

## 🚀 How to View

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `PowerBI_Project.pbix` in Power BI Desktop
4. Interact with the dashboard using slicers and cross-filtering

---

## 📚 Credits

- Dashboard built as part of a Power BI internship project
