Employee Management System
Overview
The Employee Management System is a command-line application that allows you to manage employees in a company. The system provides options to add, remove, and display employees. It ensures that each employee has a unique ID, and you can interact with the system via a simple text-based menu.

Features
Add Employee: Allows the user to input details (name, employee ID, and salary) to add a new employee to the company.
Remove Employee: Allows the user to remove an employee by their unique ID.
Display Employees: Lists all the employees currently in the company.
Exit: Exit the application.
Technologies Used
Java: The system is developed using Java, a powerful and versatile programming language.
Prerequisites
Java 8 or above installed on your machine.
A basic understanding of Java programming and object-oriented concepts.
Structure
Classes
EmployeeManagementSystem: Contains the main logic for the menu-driven interface to manage employees.
Company: A generic class that stores and manages employees using a HashMap. The key is the employee ID, and the value is the Employee object.
Methods
addEmployee(): Adds an employee to the company after validating the uniqueness of their ID.
removeEmployee(): Removes an employee from the company using their ID.
displayEmployees(): Displays all the employees in the company.