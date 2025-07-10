
# 🏥 Hospital Management System - Relational Database Project

This project is a comprehensive **Relational Database Design** for a **Hospital Management System (HMS)** created as part of an academic submission for the subject **Database Management System (DBMS)**. It includes the Entity-Relationship Diagram (ERD), SQL schema definitions, data normalization, sample inserts, and advanced queries.

## 📁 Project Structure

| File Name | Description |
|----------|-------------|
| `T210_ER-Diagram.png` | Visual ER diagram of the system |
| `T210_Relational-Schema.png` | Schema of all tables and relationships |
| `T210_ERD-RelationalSchema_and_Normalization-Proofs.pdf` | Normalization proofs up to BCNF |
| `T210_DDL_Script.txt` | SQL DDL statements to create all tables |
| `T210_INSERT_Scripts.txt` | Sample data insert scripts |
| `T210_SQL_Queries.txt` | Advanced SQL queries to analyze the database |

## 👨‍💻 Features & Modules

- Hospitals and Departments
- Doctors and their visiting schedules
- Patients and their history
- Appointments and consultations
- Staff and hospital capacity
- Medical reports and checkups

## 🧩 Database Design Overview

- **18 Tables** normalized to **BCNF**
- Primary & Foreign key constraints with cascading rules
- Full schema designed under `HMS` schema
- Uses PostgreSQL-specific features (like `EXTRACT`, `"Day"` syntax)

## 🔍 Sample SQL Queries

Some included query examples:
- Doctors available per department
- Users without consultations
- Hospital capacity tracking
- Most common medical condition
- Appointments by time period
- Most consulted doctors

View full query list in: [`T210_SQL_Queries.txt`](./T210_SQL_Queries.txt)

## 🧪 How to Use

1. **Create schema**  
   Run contents of `T210_DDL_Script.txt` in a PostgreSQL-compatible database.

2. **Insert sample data**  
   Run `T210_INSERT_Scripts.txt` to populate tables with mock data.

3. **Run analysis**  
   Use queries from `T210_SQL_Queries.txt` to extract insights and validate schema.

## 👨‍🎓 Team Members

| Name | ID |
|------|----|
| Divyarajsinh Chundavat | 202201155 |
| Tathya Prajapati | 202201170 |
| SarjilKumar Chauhan | 202201176 |
| Nitinkumar Kanzariya | 202201181 |

