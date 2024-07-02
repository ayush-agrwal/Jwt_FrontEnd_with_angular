# Angular-Spring Auth Application

A full-stack application with an Angular frontend and a Spring Boot backend, featuring user authentication and role-based access control.

## Features

- User authentication (login and registration)
- Role-based access control (Admin and User)
- Protected routes with auth guards

## Technologies

### Frontend

- Angular 17.3.8
- RxJS 7.8.1
- TypeScript 5.4.5


### Backend

- Spring Boot
- Spring Security
- JWT
- Hibernate
- MySQL

## Installation


    ```

1. Configure the database in `application.properties`.

3. Build and run:
    ```sh
    ./mvnw clean install
    ./mvnw spring-boot:run
    ```

### Frontend

1. Install dependencies and run:
    ```sh
    npm install
    ng serve
    ```

## Usage

- Open `http://localhost:4200/` in your browser.
- Register or log in with existing credentials.
- Access different sections based on your role.

