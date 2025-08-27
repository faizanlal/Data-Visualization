# Excelerate Data Visualization Virtual Internship – Learner Overview Dashboard 📊

<p align="center">
  <img width="300" height="112" src="https://github.com/user-attachments/assets/b980519a-c3f5-4cff-9769-0ad53abdba34" alt="Excelerate Dashboard Banner">
</p>

[![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue)](https://www.postgresql.org/)
[![Looker Studio](https://img.shields.io/badge/Looker_Studio-Visualization-green)](https://lookerstudio.google.com/)
[![Internship](https://img.shields.io/badge/Internship-Virtual-orange)](#)

This **interactive dashboard** provides insights into learners participating in the **Excelerate Data Visualization Virtual Internship**, showing overall counts, demographics, and distribution by **country, degree, and city**. The data processing and visualization pipeline used **SQL**, **PGAdmin 4**, and **Looker Studio**.  

---

## 📸 Visual Preview
<p align="center">
  <img width="1040" height="783" src="https://github.com/user-attachments/assets/96fa9c46-1556-4e10-a613-4c305db28939" alt="Dashboard Preview">
</p>

---

## 🗂 Data Processing

### Data Cleaning with SQL
The raw dataset included learner records with potential inconsistencies like missing values, duplicates, and formatting issues. SQL queries were used to:  

- ✅ Remove duplicate learner entries  
- ✅ Standardize categorical fields (country, degree, institution)  
- ✅ Handle missing/null values in age, city, and degree columns  
- ✅ Aggregate data for visualization purposes (e.g., total learners by country or degree)  

### Database Management
- Used **PGAdmin 4** for database management.  
- Cleaned datasets were stored in **PostgreSQL** tables for efficient querying.  
- Performed **complex joins** and aggregation queries to prepare data for visualizations.  

---

## 📊 Visualization Tool – Looker Studio
**Looker Studio** (formerly Google Data Studio) was used to create an **interactive dashboard**.  

**Features include:**  

| Feature | Description | Visualization |
|---------|-------------|---------------|
| Total Unique Learners | 132,263 learners | <p align="center"><strong>132,263</strong></p> |
| Learners by Age | Majority 18–24 years (58.5%), 25–34 years (32.8%) | <p align="center">Donut Chart</p> |
| Learners by Degree | 45.8% graduates, 39.1% undergraduates | <p align="center">Pie Chart</p> |
| Learners by Country | India: 33,116, Nigeria: 23,887, US: 14,125 | <p align="center">Bar Chart</p> |
| Learners by City | Geographic distribution of learners | <p align="center">World Heatmap</p> |

---

## 🔑 Key Takeaways

- **Demographics:** Most learners are young adults, predominantly students.  
- **Geographic Spread:** Learners mainly from **India, Nigeria, and the US**, highlighting the program’s global reach.  
- **Education Background:** Majority are graduate or undergraduate students, showing a strong academic interest in **data visualization**.  

---

## ⚙️ Tools & Technologies
- **Data Processing:** SQL, PostgreSQL, PGAdmin 4  
- **Visualization:** Looker Studio  
- **Data Cleaning & Aggregation:** SQL queries and joins  

---

Made with ❤️ by **Faizan Lal**
