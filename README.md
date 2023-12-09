# SQL Employee Tracker

## Description
The SQL Employee Tracker is a command-line application that allows users to manage departments, roles, and employees within an organization using a MySQL database. The application offers various functionalities such as viewing, adding, updating, and deleting departments, roles, and employees.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Functionality](#functionality)
- [Database Schema](#database-schema)
- [Example Data](#example-data)
- [Credits](#credits)
- [License](#license)

## Installation
1. Clone the repository: `git clone https://github.com/jellobear27/sql-employee-tracker.git`
2. Install dependencies: `npm install`
3. Set up a MySQL database and configure the connection parameters in `server.js`
4. Run the application: `npm start`

## Usage
Once installed and started, follow the command-line prompts to perform various actions related to managing departments, roles, and employees within the organization.

## Functionality
The application provides the following functionalities:
- View all departments, roles, and employees
- Add new departments, roles, and employees
- Update an employee's role
- View employees by manager
- View employees by department
- Delete departments, roles, or employees
- View the total utilized budget of a department

## Database Schema
The application uses a MySQL database with the following tables:
- `departments`: Contains department information.
- `roles`: Stores role details linked to specific departments.
- `employee`: Holds employee data with references to roles and managers.

## Example Data
Sample data has been provided in the application's SQL file, including departments, roles, and employees. The data can be viewed within the SQL file for reference.

## Credits
- **Author:** janell

## License
This project is licensed under the [MIT License](LICENSE).
