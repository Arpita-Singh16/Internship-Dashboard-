# Internship-Dashboard-
# Internship Insights Dashboard | Power BI

An interactive Power BI dashboard that summarises intern data at a glance: who the interns are, where they come from, which courses they joined, and how they performed in assessments.

> **Tools:** Power BI Desktop, DAX, Power Query, CSV / Excel data

## What the Dashboard Shows

| Visual | Chart Type | Purpose |
|---|---|---|
| Demographics | Clustered bar chart | Gender-wise student count |
| List of courses with total entries | Treemap | Which domains have the most students |
| Students by different states | Filled map | Geographic spread of interns |
| Students by joining month | Area chart | Joining trend over time |
| Interns from different colleges | Column chart | Which colleges the interns come from |
| Mode of students | Donut chart | Split by mode of study |
| Total interns | KPI card | Overall intern count |
| Assessment 1 to 5 | KPI cards | Total score for each assessment |

---

## Data Model

| Table | Key Fields Used |
|---|---|
| Student Record | Gender, College, Registration Number |
| csv (course data) | Domain, Mode, Joining, Assessment 1 to 5, Registration Number |
| State | State, Registration Number |
| Accounts | Total intern |

Tables are linked through **Registration Number**.

> **Note:** The data in this repository is **sample / anonymised** and contains no real personal information.

---

## Skills Demonstrated

- Data cleaning and transformation in Power Query
- Data modelling and relationships between tables
- DAX measures (counts, sums, KPIs)
- Choosing the right chart for each question (treemap, filled map, area, donut, column)
- Dashboard layout and visual design

---

## How to Open

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows, free).
2. Download the `.pbix` file from this repository.
3. Open it in Power BI Desktop.

---

## Repository Structure

```
.
├── INTERNSHIP_Power_bi_PAGE_2.pbix
├── images/
│   └── dashboard.png
└── README.md
```

---

## Author
**Arpita Singh**
