# Employee Management System

## Student Information

Name: Leqaa Sameh 

Student ID: 2300272

## Project Description

This project is a Java implementation of an Employee Management System based on the provided UML class diagram.

The system contains different types of employees:

- Commission Employee
- Monthly Employee
- Hourly Employee

The Department class manages employees and calculates the total payroll.

## Classes

- Employee
- CommissionEmployee
- MonthlyEmployee
- HourlyEmployee
- Department
- Gender

## OOP Concepts Used

- Encapsulation
- Inheritance
- Abstraction
- Polymorphism
- Method Overriding
- Enum
- Java Collections
- Association between classes

## Project Structure

EmployeeManagementSystem/

├── src/

│   ├── Main.java

│   ├── model/

│   │   ├── Employee.java

│   │   ├── CommissionEmployee.java

│   │   ├── MonthlyEmployee.java

│   │   ├── HourlyEmployee.java

│   │   ├── Department.java

│   │   └── Gender.java

│   │

│   └── test/

│       └── MainTest.java

└── README.md

## How to Run

1. Open the project using Apache NetBeans.
2. Make sure a compatible JDK is installed.
3. Open Main.java.
4. Run the project.
5. The program creates employees and a department.
6. It calculates employee salaries and the total department payroll.

## Salary Calculation

### Commission Employee

Commission = Sales Amount × Commission Rate

Salary = Base Salary + Commission

### Monthly Employee

Bonus = Monthly Salary × Bonus Percentage

Salary = Monthly Salary + Bonus

### Hourly Employee

The first 40 hours are considered regular hours.

Regular Salary = Regular Hours × Hourly Rate

Overtime Salary = Overtime Hours × Hourly Rate × Overtime Rate

Total Salary = Regular Salary + Overtime Salary

## Author

Leqaa Sameh
