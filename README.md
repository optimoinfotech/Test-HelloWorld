# HelloWorld

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.7.

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




Home Appliances Service Centre Management System
Overview
Welcome to the Home Appliances Service Centre Management System! This project is developed using Angular 17 for the frontend, .NET 8 for the backend API, and SQL Server as the database. The API follows a Code First approach for Entity Framework, and Web API is utilized to facilitate communication between the frontend and backend.

Table of Contents
Features
Prerequisites
Installation
Configuration
Usage
Contributing
License
Features
Angular 17 Frontend: A responsive and user-friendly web interface for managing service requests, appointments, and other aspects of a Home Appliances Service Centre.

.NET 8 Backend API: A robust and scalable API built with .NET 8, providing endpoints for CRUD operations, authentication, and other essential functionalities.

Code First Approach for Entity Framework (EF): The database schema is generated based on the code classes, simplifying database management and updates.

SQL Server Database: The system uses SQL Server as the backend database for storing information about customers, appliances, service requests, and more.

Service Centre Management: Core functionality includes managing customer information, service requests, appointments, and keeping track of appliance repairs.

Prerequisites
Before you begin, ensure you have the following installed:

Node.js and npm (for Angular)
Visual Studio or Visual Studio Code (for .NET development)
SQL Server
.NET 8 SDK
Angular CLI
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/home-appliances-service-centre.git
Navigate to the frontend and install dependencies:

bash
Copy code
cd frontend
npm install
Open the backend solution in Visual Studio or Visual Studio Code and restore NuGet packages.

Update the database connection string in the backend appsettings.json file to point to your SQL Server instance.

Configuration
Angular Configuration:

Update the API base URL in the Angular environment files to match your backend API endpoint.
.NET Configuration:

Configure the database connection string, authentication, and other settings in the appsettings.json file.
Usage
Start the Angular development server:

bash
Copy code
cd frontend
ng serve
Access the application at http://localhost:4200 in your web browser.

Run the backend API:

Start the API from Visual Studio or Visual Studio Code. The API will be accessible at http://localhost:5000.

Explore the Home Appliances Service Centre Management System and manage service requests, appointments, and customer information.

Contributing
If you would like to contribute to the project, please follow the contribution guidelines.

License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.
