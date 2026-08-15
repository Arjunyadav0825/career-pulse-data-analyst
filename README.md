# 📊 CareerPulse — Data Analyst Job Market Intelligence

CareerPulse is an end-to-end data analytics project designed to analyze job-market data and identify important patterns in **skill demand, salary, job roles, locations, AI-related skills, and candidate skill gaps**.

The project demonstrates a practical Data Analyst workflow using Python, Pandas, SQL, SQLite, and data visualization.

---

## 🚀 Project Overview

CareerPulse analyzes a job-market dataset containing information about:

- Job roles
- Locations
- Experience levels
- Salary
- Technical skills
- AI-related skills

The objective is to answer practical business questions such as:

- Which skills are most demanded?
- Which skills are associated with higher salaries?
- Which locations offer better salary opportunities?
- Which job roles have higher average salaries?
- How significant are AI-related skills?
- Which skills should candidates prioritize?

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SQLite
- SQL
- Google Colab
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Data Cleaning
- Checked dataset structure
- Checked missing values
- Checked duplicate records
- Removed duplicate records
- Prepared data for analysis

### 2. Exploratory Data Analysis
- Job distribution
- Skill demand
- Salary analysis
- Location analysis
- Experience analysis
- Role analysis

### 3. Skill Demand Analysis
Analyzed demand for:

- SQL
- Excel
- Python
- Power BI
- Tableau
- Statistics
- AWS
- Machine Learning
- GenAI
- Prompt Engineering

### 4. Salary Analysis
Analyzed salary patterns based on:

- Job role
- Location
- Required skills
- Experience

### 5. AI Skill Analysis
Analyzed demand for:

- GenAI
- Machine Learning
- Prompt Engineering

### 6. SQL Analysis
The dataset was loaded into SQLite and SQL queries were used to analyze:

- Job counts
- Average salary by location
- Skill demand
- Combined skill requirements

### 7. Skill Gap Analysis

CareerPulse also includes a basic **Skill Gap Engine** that compares a candidate's current skills against the skills observed in the analyzed job dataset.

Example candidate skills:

- SQL
- Excel
- Python
- Power BI

The model identifies missing skills and helps prioritize skills that may improve job readiness.

---

# 📈 Key Business Questions

1. Which skills are most demanded?
2. Which skills are associated with higher salaries?
3. Which locations provide better salary opportunities?
4. Which job roles have higher average salaries?
5. How significant are AI-related skills?
6. What skills should a candidate prioritize?

---

# 📊 Visualizations

## 1. Skill Demand

![Skill Demand](skill_demand.png)

This visualization compares the demand for different technical skills across the analyzed jobs.

---

## 2. Salary by Role

![Salary by Role](salary_by_role.png)

This visualization compares average salary across different job roles.

---

## 3. Salary by Location

![Salary by Location](salary_by_location.png)

This visualization compares average salary across different locations.

---

## 4. AI Skill Demand

![AI Skill Demand](ai_skill_demand.png)

This visualization compares demand for AI-related job categories and skills.

---

# 📌 Key Findings

Based on the analyzed dataset:

- Excel was among the highest-demand skills.
- AWS and GenAI showed strong demand.
- SQL and Python frequently appeared together.
- SQL, Python and Power BI appeared together in a subset of jobs.
- A significant number of analyzed jobs had salaries above 10 LPA.
- Product Analyst showed a high average salary among the analyzed roles.
- AI-related skills showed substantial demand in the dataset.

> **Note:** These findings are based on the dataset used for this project and should not be interpreted as official Indian job-market statistics.

---

# 🧠 Skill Gap Engine

CareerPulse includes a basic skill-readiness model.

It compares:

**Candidate Skills → Job-Market Skill Demand → Missing Skills → Priority Skills**

This provides a simple framework for understanding which technical skills a candidate could prioritize based on the analyzed job requirements.

---

# 🔄 Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
SQL Analysis
      ↓
Skill Analysis
      ↓
Salary Analysis
      ↓
Visualization
      ↓
Business Insights
      ↓
Skill Gap Analysis
