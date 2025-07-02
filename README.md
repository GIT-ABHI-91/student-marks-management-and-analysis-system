# student-marks-management-and-analysis-system

# 🎓 Student Performance Analysis System

## 📌 Project Overview

This is a Python-based tool to manage student academic records, store data in a MySQL database, and analyze/report performance using Pandas. The project also integrates with Power BI to provide visual insights from the same database.

---

## ⚙️ Features

- Add, update, delete student records (CRUD operations)
- Analyze marks in DBMS, DSA, and OOPJ
- View student data in tabular (DataFrame) format
- View specific student record by roll number
- Power BI dynamic dashboard connected to the database

## 🧱 Tech Stack

- **Python**
  - `pandas` for data manipulation
  - `mysql-connector-python` for MySQL operations
  - `SQLAlchemy` + `PyMySQL` for dataframe integration
- **MySQL**
  - Database: `student_data`
  - Table: `student`
- **Power BI**
  - Dynamic dashboard connected via MySQL .NET Connector


## 🏗️ Database Schema

**Database**: `student_data`  
**Table**: `student`

| Column        | Data Type          |
|---------------|--------------------|
| id            | INT, PRIMARY KEY   |
| roll_no       | INT, UNIQUE        |
| name          | VARCHAR(100)       |
| dbms_marks    | INT                |
| dsa_marks     | INT                |
| oopj_marks    | INT                |

### ✅ Prerequisites

- Python 3.8+
- MySQL Server & Workbench
- Power BI Desktop
