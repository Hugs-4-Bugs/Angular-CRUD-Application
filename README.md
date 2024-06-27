# Angular-CRUD-Application
This is a simple CRUD (Create, Read, Update, Delete) application built using Angular, HTML, CSS, and TypeScript to manage employee data.

## Features

- **Create Employee**: Add new employee records.
- **Read Employee**: View a list of all employees.
- **Update Employee**: Edit existing employee records.
- **Delete Employee**: Remove employee records from the system.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en/download/) (includes npm)
- [Angular CLI](https://angular.io/guide/setup-local)

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/employee-crud-app.git
   cd employee-crud-app
   ```

2. **Install the dependencies:**
   ```bash
   npm install
   ```

3. **Run the application:**
   ```bash
   ng serve
   ```

4. **Open the application:**
   Open your browser and navigate to `http://localhost:4200`.

## Project Structure

```
employee-crud-app/
├── src/
│   ├── app/
│   │   ├── employee/
│   │   │   ├── employee-list/
│   │   │   ├── employee-add/
│   │   │   ├── employee-edit/
│   │   │   ├── employee-delete/
│   │   ├── app-routing.module.ts
│   │   ├── app.component.html
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   ├── assets/
│   ├── environments/
│   ├── index.html
│   ├── main.ts
│   ├── styles.css
├── angular.json
├── package.json
├── README.md
```

## Usage

- **Add Employee**: Navigate to the "Add Employee" section, fill in the employee details, and submit the form.
- **View Employees**: The homepage lists all employees with options to edit or delete each entry.
- **Edit Employee**: Click the "Edit" button next to an employee's name, modify the details, and save changes.
- **Delete Employee**: Click the "Delete" button next to an employee's name to remove the entry.

## Development

For development and debugging:

- **Build the application:**
  ```bash
  ng build
  ```

- **Run tests:**
  ```bash
  ng test
  ```

- **Lint the code:**
  ```bash
  ng lint
  ```

## Contributing

Contributions are welcome! Please fork this repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README to fit the specifics of your project!
