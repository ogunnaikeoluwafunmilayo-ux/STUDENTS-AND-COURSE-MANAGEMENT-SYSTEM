# STUDENTS-AND-COURSE-MANAGEMENT-SYSTEM- SQL 

<img width="1192" height="617" alt="Database design" src="https://github.com/user-attachments/assets/93ea98fd-ab04-4e8a-9128-93ccf13da302" />

<img width="1192" height="630" alt="Analytical insights" src="https://github.com/user-attachments/assets/a5ee95b2-4251-498a-bb49-408fc8086246" />

<img width="1197" height="630" alt="Business Reporting" src="https://github.com/user-attachments/assets/943471a9-eedf-4643-bbc7-e963cb23992d" />

# Student & Course Management System — SQL Analysis

## Project Overview
A fully normalized relational database built for a simulated academic institution 
to enable data driven decisions across student management, course performance 
and instructor evaluation.

---

## Key Statistics
| Metric | Value |
|---|---|
| Total Students | 24 |
| Total Courses | 8 |
| Total Instructors | 6 |
| Total Enrollments | 48 |
| Overall Average Score | 77.27 |
| Pass Rate | 100% |

---

## Database Schema
Five normalized tables with Primary Keys and Foreign Keys:
- **Students** — student demographics and records
- **Courses** — course information linked to instructors
- **Instructors** — instructor details
- **Enrollments** — links students to courses
- **Grades** — student scores per enrollment

![Database Design & ERD](database-design.png)

---

## Key SQL Queries Executed
- Student enrollment tracking and demographic analysis
- Course average scores and rankings
- Instructor performance evaluation
- Students scoring above/below thresholds
- Window functions for student ranking (RANK())
- Subqueries to identify above-average performers
- Pass rate calculation per course

---

## Key Insights Discovered
- **Best Instructor:** David Anthony — Avg Score: 85.67
- **Top Course:** IAS — Avg Score: 85.67
- **Needs Attention:** Finance course recorded the lowest average (67.83)
- **Star Performers:** 12 students scored above the 77.27 overall average
- **100% Pass Rate** — No student scored below 50 across all courses
- All 8 courses exceeded 5 enrolled students — balanced enrollment load

![Analytical Insights Dashboard](analytical-insights.png)

---

## Business Reporting
![Business Reporting](business-reporting.png)

---

## Business Recommendations
1. Integrate this SQL database with Power BI for live academic dashboards
2. Build an early warning system to flag students scoring below 60
3. Use enrollment data to balance instructor course loads
4. Expand schema to include attendance, assignments and semesters

---

## Author
**Hannah Ogunnaike**

[LinkedIn](https://www.linkedin.com/in/hannah-ogunnaike-439661280) | 
[GitHub](https://github.com/ogunnaikeoluwafunmilayo-ux)
