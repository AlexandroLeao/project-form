# Project-Form

This is a sample project that demonstrates the creation of a CRUD (Create, Read, Update, Delete) application using Angular and Angular Material. The project also utilizes a JSON server as a mock API for handling data.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed in your development environment:

- Node.js: [Install Node.js](https://nodejs.org)
- Angular CLI: Install the Angular CLI globally by running the following command in the terminal:

npm install -g @angular/cli

- JSON server: Install JSON server globally by running the following command in the terminal:

npm install -g json-server

## Installation

Follow the steps below to set up and run the CRUD-APP project:

1. Clone this repository:

https://github.com/AlexandroLeao/project-form.git

2. Navigate to the project folder:

cd crud-app

3. Install project dependencies:

npm install

4. Start the JSON server for the mock API:

json-server --watch db.json

5. In a separate terminal, start the development server for the CRUD-APP:

ng serve


6. Access the application in your browser through the following address: `http://localhost:4200/`

## API

The CRUD-APP uses a JSON server as a mock API to handle data. The server is set up to use the `db.json` file located in the project's root directory. You can modify this file to add, edit, or delete data.

The API endpoints are as follows:

- GET all employees: `http://localhost:3000/employees`
- GET a specific employee: `http://localhost:3000/employees/{id}`
- POST a new employee: `http://localhost:3000/employees`
- PUT update an existing employee: `http://localhost:3000/employees/{id}`
- DELETE an employee: `http://localhost:3000/employees/{id}`

## Features

The CRUD-APP has the following features:

- Add Employee: Fill out the registration form to add a new employee.
- Edit Employee: Click the "Edit" button to modify the data of an existing employee.
- Delete Employee: Click the "Delete" button to remove an employee from the list.
- Search Employee: Use the search bar to filter employees based on their name.

## Project Structure

The project structure consists of the following files and directories:

csharp
Copy code
crud-app/
├── src/
│   ├── app/
│   │   ├── app-routing.module.ts
│   │   ├── app.component.html
│   │   ├── app.component.scss
│   │   ├── app.component.spec.ts
│   │   ├── app.component.ts
│   │   └── app.module.ts
│   ├── assets/
│   │   └── index.html
│   ├── main.ts
│   └── styles.scss
└── emp-add-edit/
    ├── emp-add-edit.component.html
    └── emp-add-edit.component.ts
    
-app-routing.module.ts: Manages the application routes.
-app.component.html: Defines the structure of the application interface, including the toolbar, search column, and employee data table.
-app.component.scss: Defines the style of the application.
-app.component.spec.ts: Contains unit tests for the AppComponent component.
-app.component.ts: Implements the logic for data manipulation and interaction with services.
-app.module.ts: Defines the main module of the application, importing and configuring necessary modules.
-assets/: Contains additional files, such as index.html, defining the basic HTML structure of the application page.
-main.ts: Initializes the application module.
-styles.scss: Defines global styles for the application.
-emp-add-edit.component.html: Defines the structure of the employee registration and editing form.
-emp-add-edit.component.ts: Contains the logic for employee registration and editing.

## Technologies Used

- Angular
- Angular Material
- JSON server

## Contribution

Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
