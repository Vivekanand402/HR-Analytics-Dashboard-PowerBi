# HR-Analytics-Dashboard-PowerBi
# HR Analytics Dashboard | Power BI

## 📌 Project Overview

This project is an interactive **HR Analytics Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes employee data to understand **employee attrition, workforce demographics, salary patterns, job roles, education, and years at the company**.

The purpose of this project is to help HR teams identify factors affecting employee attrition and support data-driven employee retention decisions.

---

## 🎯 Objectives

- Analyze overall employee attrition.
- Calculate and monitor attrition rate.
- Identify employee groups with higher attrition.
- Analyze attrition by age, education, salary, and job role.
- Analyze employee attrition based on years at the company.
- Provide meaningful insights for HR decision-making.

---

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## 📊 Dashboard KPIs

- Total Employees: **1,470**
- Total Attrition: **238**
- Attrition Rate: **16.2%**
- Average Age: **37**
- Average Salary: **6.5K**
- Average Years at Company: **7.0**

---

## 📈 Dashboard Analysis

The dashboard provides analysis of:

- Attrition by Education
- Attrition by Age Group
- Attrition by Salary Slab
- Attrition by Job Role
- Attrition by Years at Company
- Attrition by Gender

---

## 🧹 Data Preparation

The data was prepared using Power Query.

Steps included:

- Data cleaning
- Removing duplicate records
- Handling missing values
- Changing data types
- Standardizing data
- Creating age groups
- Creating salary slabs
- Preparing data for analysis

---

## 🧮 DAX

Some key measures created for the dashboard:

### Total Employees

```DAX
Total Employees = COUNTROWS(EmployeeData)
