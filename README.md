# 📊 CareerPulse — Data Analyst Job Market Intelligence

CareerPulse is an end-to-end **Data Analytics project** designed to analyze job-market data and identify important patterns in **skill demand, salaries, job roles, locations, AI-related skills, and candidate skill gaps**.

The project demonstrates a practical Data Analyst workflow using **Python, Pandas, NumPy, SQL, SQLite, Matplotlib, and Google Colab**.

> ⚠️ **Dataset Note:** This project uses a synthetic dataset created for analytical methodology demonstration. The results should not be interpreted as actual Indian job-market statistics.

---

## 🚀 Project Overview

CareerPulse analyzes job-market data containing information about:

- 💼 Job Roles
- 📍 Locations
- 🎓 Experience Levels
- 💰 Salaries
- 🛠️ Technical Skills
- 🤖 AI-related Skills

The project was created to answer practical business questions such as:

1. Which technical skills are most demanded?
2. Which skills are associated with higher salaries?
3. Which locations offer better salary opportunities?
4. Which job roles have higher average salaries?
5. How significant are AI-related skills?
6. Which skills should candidates prioritize?

---

## 🛠️ Tools & Technologies

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🗄️ SQLite
- 🔎 SQL
- ☁️ Google Colab
- 📓 Jupyter Notebook

---

## 🔄 Project Workflow

```text
Data Generation
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
SQL Analysis
      ↓
Salary Analysis
      ↓
Skill Demand Analysis
      ↓
Location & Role Analysis
      ↓
AI Skill Analysis
      ↓
Visualization
      ↓
Skill Gap Analysis
      ↓
Business Insights
```

---

# 🔍 Analysis Performed

## 1. Data Cleaning

The project performs basic data-quality checks including:

- Dataset structure inspection
- Missing-value analysis
- Duplicate-value analysis
- Duplicate removal
- Data-type verification
- Data preparation

---

## 2. Exploratory Data Analysis

The project analyzes:

- Total number of jobs
- Average salary
- Median salary
- Salary patterns
- Skill demand
- Job roles
- Locations
- Experience levels

---

## 3. SQL Analysis

SQLite and SQL are used to perform analytical queries such as:

- Job count by location
- Average salary by location
- Skill-wise job demand
- SQL + Python job demand
- SQL + Python + Power BI job demand
- AI-related job demand

Example:

```sql
SELECT
    Location,
    COUNT(*) AS Job_Count,
    ROUND(AVG(Salary_LPA), 2) AS Average_Salary
FROM jobs
GROUP BY Location
ORDER BY Job_Count DESC;
```

---

## 4. Skill Demand Analysis

The project analyzes demand for:

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

---

## 5. Salary Analysis

Salary patterns are analyzed according to:

- Job Role
- Location
- Required Skill
- Experience Level

---

## 6. AI Skill Analysis

The project specifically analyzes AI-related skills:

- 🤖 GenAI
- 🧠 Machine Learning
- ✨ Prompt Engineering

This helps demonstrate how AI-related skills can be incorporated into job-market analysis.

---

## 7. Skill Gap Analysis

CareerPulse includes a basic **Skill Gap Engine** that compares a candidate's current skills with the skills observed in the analyzed job dataset.

It identifies:

- Current skills
- Missing skills
- Priority skills
- Skill readiness score

Example:

```text
Candidate Skills
      ↓
SQL
Excel
Python
Power BI
      ↓
Compare with Job-Market Skills
      ↓
Identify Missing Skills
      ↓
Calculate Skill Readiness
      ↓
Recommend Priority Skills
```

---

# 📊 Visualizations

The project includes four major visualizations generated using Python and Matplotlib.

## 1. 📈 Skill Demand

This chart compares the demand for different technical skills across the analyzed jobs.

![Skill Demand](./skill_demand.png)

---

## 2. 💰 Salary by Role

This chart compares the average salary across different job roles.

![Salary by Role](./salary_by_role.png)

---

## 3. 📍 Salary by Location

This chart compares salary levels across different locations.

![Salary by Location](./salary_by_location.png)

---

## 4. 🤖 AI Skill Demand

This chart shows the demand for AI-related skills including GenAI, Machine Learning, and Prompt Engineering.

![AI Skill Demand](./ai_skill_demand.png)

---

# 🎯 Business Questions

| # | Business Question |
|---|---|
| 1 | Which skills are most demanded? |
| 2 | Which skills are associated with higher salaries? |
| 3 | Which locations provide better opportunities? |
| 4 | Which roles have higher average salaries? |
| 5 | How significant are AI-related skills? |
| 6 | What skills should a candidate prioritize? |

---

# 📈 Key Findings

Based on the analyzed synthetic dataset:

- 📌 Excel was among the highest-demand skills.
- 📌 AWS and GenAI showed strong skill demand.
- 📌 188 jobs required both SQL and Python.
- 📌 72 jobs required SQL, Python, and Power BI together.
- 📌 504 jobs had salaries above 10 LPA.
- 📌 Product Analyst had the highest average salary among the analyzed roles.
- 📌 Remote roles showed strong salary performance in the analyzed dataset.
- 📌 AI-related skills showed significant demand across the dataset.

> ⚠️ These findings are based on a synthetic dataset and are intended for demonstration purposes only.

---

# 🧠 Skill Gap Engine

The Skill Gap Engine provides a simple candidate-readiness analysis.

It compares:

```text
Candidate Skills
       ↓
Job-Market Skill Requirements
       ↓
Skill Comparison
       ↓
Missing Skills
       ↓
Priority Skills
       ↓
Skill Readiness Score
```

This adds a candidate-focused analytical layer to the project.

---

# 🗄️ Database

The project uses SQLite for database analysis.

### Database

```text
careerpulse.db
```

### Main Table

```text
jobs
```

The database is used to perform SQL-based analysis on the job dataset.

---

# 📁 Project Structure

```text
career-pulse-data-analyst/
│
├── career-pulse-data-analyst.ipynb
├── CareerPulse_Data_Analyst_Project.ipynb
│
├── skill_demand.png
├── salary_by_role.png
├── salary_by_location.png
├── ai_skill_demand.png
│
├── careerpulse.db
│
└── README.md
```

---

# ▶️ How to Run the Project

## ☁️ Google Colab

1. Open the `.ipynb` notebook in Google Colab.
2. Run the cells sequentially.
3. The notebook performs:
   - Data generation
   - Data cleaning
   - Exploratory analysis
   - SQL analysis
   - Salary analysis
   - Skill analysis
   - AI skill analysis
   - Visualization
   - Skill gap analysis

---

## 💻 Jupyter Notebook

Install the required packages:

```bash
pip install pandas numpy matplotlib
```

Then start Jupyter:

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially.

---

# 💡 Skills Demonstrated

## Python

- Pandas
- NumPy
- Data manipulation
- Data analysis

## SQL

- SELECT
- GROUP BY
- COUNT
- SUM
- AVG
- Filtering
- Aggregation
- SQLite

## Data Analytics

- Data Cleaning
- Exploratory Data Analysis
- KPI Analysis
- Salary Analysis
- Skill Demand Analysis
- Location Analysis
- Role Analysis
- AI Skill Analysis
- Skill Gap Analysis

## Data Visualization

- Bar Charts
- Salary Comparisons
- Skill Demand Visualization
- Location Analysis
- AI Skill Visualization

## Business Analysis

- Business Question Identification
- KPI Identification
- Insight Generation
- Candidate Skill Recommendations

---

# ⭐ Project Highlights

### 🔹 End-to-End Data Analytics

```text
Raw Data
   ↓
Data Cleaning
   ↓
SQL
   ↓
Analysis
   ↓
Visualization
   ↓
Insights
   ↓
Skill Gap Analysis
```

### 🔹 Business-Oriented Analysis

The project focuses on practical questions related to:

- Hiring
- Salary
- Skills
- Locations
- AI adoption
- Candidate readiness

### 🔹 Candidate Intelligence

The Skill Gap Engine demonstrates how job-market data can be used to identify missing and high-priority skills for candidates.

---

# ⚠️ Dataset Disclaimer

This project uses a **synthetically generated dataset**.

The dataset was created for demonstrating:

- Data Analytics
- SQL
- Data Visualization
- Business Analysis
- Skill Gap Analysis

Therefore, the numerical results should **not** be considered actual Indian job-market statistics.

---

# 👨‍💻 Author

## Arjun Kumar Yadav

**Computer Science Engineering Graduate | Data Analyst | Frontend Developer | AI & Data Enthusiast**

---

# 📌 Project Summary

CareerPulse demonstrates an end-to-end Data Analyst workflow:

```text
Data
 ↓
Cleaning
 ↓
SQL
 ↓
Analysis
 ↓
Visualization
 ↓
Insights
 ↓
Skill Gap Analysis
```

The project combines technical analysis with business-oriented insights to demonstrate practical Data Analyst capabilities.

---

## ⭐ Portfolio Project

This project was created as a portfolio demonstration of practical Data Analytics, SQL, Python, visualization, and business-analysis skills.
