# Employe-Data-Management-System
A Python-based application to manage employee data with functionalities like adding, updating, searching, and storing employee records in a CSV file.

Project Description:
When the user starts the program ,he is presented with a menu of actions (add, update, delete, search, list, exit).
Depending on the selected option, the program performs the corresponding task (e.g., adding or updating an employee).
If the user chose Add Employee, he will enter employee details like ID, Name, Position, Salary, and Email. These details will be saved to the CSV file for persistent storage.
If the user chose Update Employee, the user will be asked to choose the feature he wants to update depending on the employee id.
If the user chose Delete Employee, the user will be asked to enter the ID of the employee he wants to delete. The CSV file will automatically be updated after deletion.
If the user chose Search Employee, the user will be asked to enter the ID of the employee he wants to search for.
If the user chose List All Employees, all employees details will be displayed.
If the user chose Exit, the program will be terminated.

File Handling:
Employee data will be stored in a CSV file for long-term access.
Data will be loaded from the file when the program starts.

Error Handling:
Basic validation for input data like checking valid emails or numeric salary and ID values.
Validate the search functionality retrieves the correct employee or returns "not found" if the ID doesn’t exist.
Validate the Add functionality add the  employee or returns "Employee already exists" based on his ID.
