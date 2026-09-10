# 📊 IBM HR Analytics Employee Attrition Analysis Using Python

## 📌 Project Overview

This project analyzes **employee attrition and workforce patterns** using Python. The analysis focuses on understanding the factors associated with employee turnover, including **age, income, job role, overtime, job satisfaction, work-life balance, experience, and career growth**.

The project was completed using **Google Colab** with Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Objectives

* Analyze overall employee attrition.
* Identify employee groups with higher attrition.
* Analyze the relationship between income and attrition.
* Study job satisfaction and work-life balance.
* Analyze the impact of overtime on attrition.
* Analyze employee experience and career progression.
* Identify high-risk job roles and departments.
* Provide HR recommendations to improve employee retention.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab**
* **GitHub**

---

## 📂 Dataset

**IBM HR Analytics Employee Attrition & Performance Dataset**

The dataset contains employee information such as:

* Age
* Attrition
* Business Travel
* Department
* Job Role
* Monthly Income
* Job Level
* Overtime
* Job Satisfaction
* Environment Satisfaction
* Relationship Satisfaction
* Work-Life Balance
* Total Working Years
* Years at Company
* Years in Current Role
* Years Since Last Promotion
* Years With Current Manager

---

## 🧹 Data Cleaning & Preparation

The following steps were performed:

* Checked dataset dimensions and data types.
* Checked missing values.
* Checked duplicate records.
* Checked unique values.
* Removed unnecessary identifier and constant columns.
* Checked numerical values for inconsistencies.
* Created additional features for analysis.

### Removed Columns

```python
EmployeeNumber
EmployeeCount
StandardHours
Over18
```

### Feature Engineering

The following features were created:

* `Age_Group`
* `Income_Group`
* `Experience_Group`
* `Attrition_Flag`

`Attrition_Flag` converts employee attrition into a numerical format:

```text
Yes → 1
No  → 0
```

This was used for correlation analysis.

---

## 🔍 Analysis Performed

### 👥 Employee Analysis

* Total employees
* Average age
* Average monthly income
* Average total working experience
* Average years at company
* Job role analysis
* Department analysis
* Job level analysis

### 📉 Attrition Analysis

* Overall attrition rate
* Attrition by department
* Attrition by job role
* Attrition by overtime
* Attrition by business travel
* Attrition by marital status
* Attrition by gender
* Attrition by age group
* Attrition by income group
* Attrition by experience group

### 😊 Satisfaction Analysis

* Job satisfaction distribution
* Job satisfaction vs attrition
* Environment satisfaction vs attrition
* Relationship satisfaction vs attrition
* Work-life balance vs attrition
* Job involvement vs attrition

### 📈 Experience & Career Analysis

* Total working experience vs attrition
* Years at company vs attrition
* Years in current role vs attrition
* Years since last promotion vs attrition
* Years with current manager vs attrition
* Job level vs attrition

### 🔎 Advanced Analysis

* Department + job role attrition
* Age group + overtime attrition
* Income group + overtime attrition
* Job role + overtime attrition
* Business travel + overtime attrition
* Distance from home vs attrition
* Factors most strongly associated with attrition
* Employee profiles most likely to leave or stay

---

## 📊 Main Visualizations

The project includes the following key visualizations:

```text
visualizations/
│
├── attrition_rate.png
├── attrition_by_department.png
├── attrition_by_job_role.png
├── attrition_by_overtime.png
├── attrition_by_job_satisfaction.png
├── attrition_by_age_group.png
├── attrition_by_income_group.png
├── age_vs_monthly_income.png
├── job_level_vs_monthly_income.png
├── attrition_by_experience_group.png
├── worklife_balance_vs_attrition.png
└── department_jobrole_attrition.png
```

These visualizations help communicate the major HR and employee-retention findings clearly.

---

## 💡 Key Insights

The analysis identifies employee attrition patterns related to:

* Overtime
* Monthly income
* Job role
* Job satisfaction
* Work-life balance
* Age
* Experience
* Job level
* Career progression
* Distance from home

The analysis helps identify **employee segments with comparatively higher attrition rates** and provides a basis for targeted HR retention strategies.

---

## 🧠 HR Recommendations

Based on the analysis, HR teams can consider:

* **Reduce excessive overtime** through better workload management.
* **Improve work-life balance** and employee wellbeing.
* **Review compensation** for employee groups with higher attrition.
* **Provide career growth opportunities** and clearer promotion paths.
* **Improve employee engagement and job involvement.**
* **Monitor high-attrition job roles and departments.**
* **Provide training and development opportunities.**
* **Support employees facing long commuting distances** where distance is associated with higher attrition.
* **Use employee data to identify high-risk groups early** and develop targeted retention strategies.

---

## 📌 Conclusion

This project demonstrates how **Python and Exploratory Data Analysis (EDA)** can be used to analyze employee attrition and discover meaningful workforce patterns.

The analysis provides HR-focused insights into **employee satisfaction, overtime, income, experience, job roles, career growth, and work-life balance**, helping organizations make more informed employee-retention decisions.

---

## 🚀 Skills Demonstrated

**Python | Pandas | NumPy | Data Cleaning | EDA | Data Visualization | GroupBy | Crosstab | Correlation Analysis | HR Analytics | Business Insights**

---

## 👨‍💻 Author

**Anoop KS**

Aspiring Data Analyst

**Skills:** Python | SQL | Excel | Power BI | Tableau
