# 832202120_contacts_frontend


```markdown
# Employee Management System

## Overview

This Vue application is a simple employee management system that allows users to manage employee data through a clean and intuitive interface. The system includes features such as searching, adding, editing, and deleting employee records.

## Features

- **Search Employee**: Search employees by name.
- **Add Employee**: Add new employees to the system.
- **Edit Employee**: Update existing employee information.
- **Delete Employee**: Remove employees from the system, with support for both single and batch deletion.
- **Pagination**: Navigate through pages of employee records.

## Screenshots

![Employee Management System](https://url-to-screenshot-1)
![Add/Edit Employee Dialog](https://url-to-screenshot-2)

## Setup

To run the application, follow these steps:

1. Clone the repository:
   ```
   git clone [repository-url]
   ```
   Replace `[repository-url]` with the URL of your repository.

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run serve
   ```

## Usage

- **Search**: Enter a name into the search input and click the search button to filter employees.
- **Add**: Click the "add new people" button to open the add employee dialog. Fill in the details and save.
- **Edit**: Click the "Edit" button in the action column of the table to modify an employee's details.
- **Delete**: Click the "Delete" button to remove a single employee or select multiple employees and use the "Batch deletion" button.

## API Endpoints

The application communicates with the backend through the following API endpoints:

- `GET /employee/selectPage`: Retrieves a paginated list of employees.
- `POST /employee/add`: Adds a new employee.
- `PUT /employee/update`: Updates an existing employee.
- `DELETE /employee/deleteById/{id}`: Deletes an employee by ID.
- `DELETE /employee/deleteBatch`: Deletes multiple employees.

## Data Model

The `Employee` data model includes the following fields:

- `name`: The employee's name.
- `sex`: The employee's gender.
- `descr`: Additional remarks or notes about the employee.
- `phoneNumber`: The employee's contact number.

## Contributing

Contributions are welcome! Please submit a pull request with your improvements.

## License

This project is open source and available under the [MIT License](LICENSE).
```


