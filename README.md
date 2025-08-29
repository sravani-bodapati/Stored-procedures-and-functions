
## Stored Procedures and Functions in SQL
# Introduction
This project demonstrates the use of stored procedures and stored functions in SQL within an employee database. It highlights how procedural SQL elements can be used to encapsulate logic, improve reusability, and simplify database operations.

# Database Overview
- Database Name: EMPLOYEES
- Table: EMP
- Columns:
- EMP_ID – Unique identifier for each employee
- EMP_NAME – Name of the employee
- DEPARTMENT – Department or email (used as department field here)
- SALARY – Salary of the employee
Sample employee data is inserted for demonstration.

# Stored Procedure
# Purpose
The stored procedure GETEMPLOYEEBYDEPT retrieves all employees from a specific department, displaying their names and salaries.

# How it Works

- Takes one input parameter: DEPARTMENT
- Queries the EMP table to find employees belonging to that department
- Returns a list of employee names along with their salaries

# Stored Function
# Purpose
 stored function AVGDEPTSALARY calculates the average salary for employees within a given department.

# How it Works

- Accepts one input parameter: DEPARTMENT
- Computes the average salary of employees in that department
- Returns the computed average as a result

 # Sample Results

- Procedure Example Output: List of employees with salaries in a given department
- Function Example Output: Average salary for the specified department

🎯 Key Learning Outcomes

How to create a
