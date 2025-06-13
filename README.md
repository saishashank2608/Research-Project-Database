# 📊 Research Projects Database

This project is a **Research Projects Database** designed to manage and track essential information related to research projects, employees, funding agencies, and project management using a relational database model.

## 📁 Overview

The database schema handles:

- 📌 **Projects** with details like name, manager, budget, duration, and funding agency.
- 👩‍💼 **Employees** who can work on multiple projects and may also serve as project managers.
- 💰 **Funding Agencies** that fund research projects.
- 🔗 Relationships between employees and projects.

## 🧠 Real-World Assumptions

- Each **project** is funded by a **single agency**.
- **Project names** are unique within a **funding agency**.
- An **employee** can work on multiple projects.
- A **manager** is also an employee.
- A project has only **one manager**.

## 🛠️ SQL Tables

The project includes the following tables:

1. **Employee** – Stores employee details.
2. **FundingAgency** – Stores details of funding agencies.
3. **Project** – Stores project-specific data.
4. **Project_Manager** – Maps each project to its manager.
5. **Employee_Project** – Many-to-many relation between employees and projects.

## 🗂️ Table Creation Scripts

SQL scripts are provided to:

- Create all the necessary tables.
- Define appropriate primary and foreign key relationships.
- Insert sample data for demonstration and testing.

## 📦 Sample Data

Includes realistic entries for:

- Employees (with SSN, name, salary)
- Projects (with ID, name, duration, and budget)
- Funding agencies (with ID, name, and address)
- Project managers
- Employee-project participation

## 📌 Usage

- Clone or download the repository.
- Run the SQL scripts in your preferred SQL environment (e.g., MySQL Workbench).
- Use the schema to practice querying, joins, and relationships in SQL.

## 🔗 Relations Summary

- Each **project** has:
  - One **manager** (`Project_Manager`)
  - One **funding agency**
- Each **employee** can:
  - Work on multiple **projects** (`Employee_Project`)
  - Be a **manager** of a project

## 🧠 Learning Objectives

- Understanding of entity-relationship modeling.
- Practice in SQL table creation and relational constraints.
- Handling many-to-many and one-to-many relationships.

![image](https://github.com/user-attachments/assets/e877769e-361f-4b2f-8dec-3dc86818997b)

![image](https://github.com/user-attachments/assets/ffcb4ba0-3d35-46ee-8ab8-574840797689)


Made with ❤️ for database learning and practice.

