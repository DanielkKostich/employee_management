# employee_management

The Employee Management CLI Application is a powerful tool that allows business owners to efficiently manage departments, roles, and employees within their company. It provides an intuitive command-line interface to organize and plan your business effectively.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine using the following command:
git clone https://github.com/DanielkKostich/employee_management


2. Navigate to the project directory:
cd employee_management



3. Install the required dependencies:
npm install

4. Set up the database:
- Create a new database using your preferred relational database management system (RDBMS) such as MySQL, PostgreSQL, or SQLite.
- Configure the database connection details in the application by modifying the `connection.js` file.

## Usage

To start the application, run the following command:
npm start



Follow the instructions provided in the command-line interface to interact with the application. The main menu offers a variety of options to view and manage departments, roles, and employees.

## Features

The Employee Management CLI Application offers the following features:

- **View all departments:** Displays a formatted table showing the names and IDs of all departments.

- **View all roles:** Presents a formatted table with job titles, role IDs, department names, and salaries for each role.

- **View all employees:** Shows a formatted table with employee details, including IDs, first names, last names, job titles, departments, salaries, and managers.

- **Add a department:** Allows you to add a new department to the database by entering the department name.

- **Add a role:** Enables you to add a new role to the database by providing the role name, salary, and associated department.

- **Add an employee:** Lets you add a new employee to the database by entering their first name, last name, role, and manager.

- **Update an employee role:** Allows you to update an employee's role by selecting the employee and specifying the new role.

## Contributing

Contributions to the Employee Management CLI Application are welcome! If you have any ideas, suggestions, or bug fixes, please submit a pull request. Make sure to follow the existing code style and provide comprehensive documentation for your changes.

## License

This project is licensed under the [MIT License](LICENSE).