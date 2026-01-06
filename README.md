# Bash-Database-engine

A lightweight, terminal-based Database Management System (DBMS) built entirely using **Bash Scripting**. This project simulates a relational database environment where you can manage databases and tables through a command-line interface.

## 🛠️ How it Works
- Run ./main to start.

## 🚀 Features
- **Database Management**: Create, List, and Drop databases.
- **Table Management**:
  - Create tables with specific schemas (Columns & Data Types).
  - Define a **Primary Key** for each table.
- **Data Operations (CRUD)**:
  - **Insert**: Add new records with data type validation.
  - **Select**: Query and display data in a formatted table.
  - **Update**: Modify existing records based on specific criteria.
  - **Delete**: Remove records safely.
- **Data Integrity**: 
  - Prevents duplicate Primary Keys.
  - Validates Integer vs String data types.

## 📁 Project Structure
Bash-DBMS/
|── main       # السكريبت الرئيسى اللى هتشغله عشان يوصلك للمينو
|── controlDB  # سكريبت بيستدعيه الmain تلقائيا عند اختياؤ "connect to database"
|── databases/ # المسار اللى هتتخزن فيه الdatabases
|   |── DB1/
|   |  |── table1 
|   |  |── table2 
|   |── DB2/
|── README.md  

