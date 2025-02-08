
**GestionCompetence Project Overview**
=====================================

### Project Description

The GestionCompetence project is a full-stack application, consisting of a Java-based web application built using the Spring Boot framework, and a front-end built using Angular.

**Back-end**

The back-end is a competence management system, likely designed for organizations to manage employee skills and competencies.

### Technologies Used

#### Back-end

* **Java 17**: The primary programming language used for developing the application.
* **Spring Boot**: A popular Java framework for building web applications, providing a robust and flexible foundation for the project.
* **Spring Data JPA**: A framework for simplifying database interactions, providing a layer of abstraction between the application and the database.
* **Lombok**: A library used to reduce boilerplate code, providing annotations for automatic generation of getters, setters, and constructors.
* **OpenCSV**: A library for reading and writing CSV files, potentially used for importing/exporting data.
* **SpringDoc OpenAPI**: A library for generating API documentation, providing a UI for exploring and testing API endpoints.
* **MySQL**: A relational database management system used to store application data.
* **Maven**: A build automation tool used to manage project dependencies, compile, and package the application.
* **OAuth2 Resource Server**: Support for OAuth2 authentication and authorization, potentially used for securing API endpoints.
* **Spring Boot Test**: A testing framework for writing unit tests and integration tests.
* **Spring Boot DevTools**: A set of tools for improving developer productivity, including automatic restart and debugging features.
* **JavaMail**: A library for sending emails, potentially used for notifications or alerts.

#### Front-end

* **Angular**: A popular JavaScript framework for building web applications, providing a robust and flexible foundation for the project.
* **Angular CLI**: A command-line interface for building, testing, and deploying Angular applications.

### Features

* **Web Application**: A web-based interface for users to interact with the application.
* **Database Management**: Integration with a MySQL database for storing and retrieving data.
* **API Documentation**: Automatic generation of API documentation using SpringDoc OpenAPI.
* **CSV Import/Export**: Support for importing and exporting data in CSV format using OpenCSV.
* **Email Sending**: Integration with a mail server for sending emails, potentially used for notifications or alerts.
* **OAuth2 Resource Server**: Support for OAuth2 authentication and authorization, potentially used for securing API endpoints.
* **Testing**: Integration with Spring Boot Test for writing unit tests and integration tests.

### Development

#### Back-end

* **Development Server**: Run `mvn spring-boot:run` to start the back-end development server.
* **Build**: Run `mvn package` to build the back-end project.
* **Testing**: Run `mvn test` to execute unit tests and integration tests.

#### Front-end

* **Development Server**: Run `ng serve` to start the front-end development server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.
* **Code Scaffolding**: Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.
* **Build**: Run `ng build` to build the front-end project. The build artifacts will be stored in the `dist/` directory.
* **Running Unit Tests**: Run `ng test` to execute the unit tests via Karma.
* **Running End-to-End Tests**: Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

### Additional Notes

The project uses a Maven-based build process for the back-end, with a `pom.xml` file defining dependencies, plugins, and configurations. The front-end uses the Angular CLI for building, testing, and deploying the application. The use of Lombok and Spring Boot DevTools suggests a focus on developer productivity and ease of development.
