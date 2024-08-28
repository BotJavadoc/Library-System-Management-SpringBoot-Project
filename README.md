# Java, Spring Boot Mini Project - Library Management System
 Admin Login User Id: ```admin``` & Password: ```admin```

# Library Management System

This is a Library Management System built using Spring Boot that follows the MVC (Model-View-Controller) architecture. The system allows administrators to manage library resources and users to search for and borrow books. This project also includes user authentication and authorization mechanisms.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [Contact](#contact)

## Features

- User authentication and authorization (Admin and User roles).
- Add, edit, delete, and view books.
- Search books by title, author, or category.
- Borrow and return books.
- Manage user accounts.
- Responsive user interface.

## Technologies Used

- **Backend**: Spring Boot, Spring MVC, Spring Security, Hibernate
- **Frontend**: JSP, HTML, CSS, JavaScript
- **Database**: H2 
- **Build Tool**: Maven

## Architecture

This project follows the MVC (Model-View-Controller) architecture:

- **Model**: Represents the data and the business logic. It includes entities and services.
- **View**: User interface layer using JSP, HTML, CSS, and JavaScript.
- **Controller**: Handles the requests and responses, connecting the model and the view.

## Installation

### Prerequisites

- Java 11 or higher
- Maven 3.6 or higher
- MySQL 8.0 or higher

### Steps

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/library-management-system.git
    cd library-management-system
    ```

2. **Configure the database**:

    - Open `src/main/resources/application.properties`.
    - Set your MySQL database configuration:

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/library_db
    spring.datasource.username=yourusername
    spring.datasource.password=yourpassword
    spring.jpa.hibernate.ddl-auto=update
    ```

3. **Build the project**:

    ```bash
    mvn clean install
    ```

4. **Run the application**:

    ```bash
    mvn spring-boot:run
    ```

5. **Access the application**:

    - Open your browser and go to `http://localhost:9080`.

## Usage

1. **Login**:
    - Admin can login to manage books and users.
    - Users can login to search for and borrow books.

2. **Admin**:
    - Manage books (add, edit, delete).
    - Manage user accounts.

3. **User**:
    - Search for books by title, author, or category.
    - Borrow and return books.

## Screenshots

### Login Page
![login page](https://github.com/user-attachments/assets/bd27f5e9-5977-48be-bc1e-e5e4b3121641)

### Add Book
![add book](https://github.com/user-attachments/assets/b396f87e-3d49-495b-afea-70304c31bb78)

### Books List
![add book](https://github.com/user-attachments/assets/8fe97f7c-ca15-4886-978b-f62f9baf830f)

### Auth List

![auth page](https://github.com/user-attachments/assets/aa10387c-c883-477f-99ae-13d77df5a9a4)

### Add Auth

![add auth](https://github.com/user-attachments/assets/b64a49a9-7482-4979-b7d5-2212d32748c0)


## Contributing!


Contributions are welcome! Please fork the repository and create a pull request.


## Contact

For any inquiries, please contact [Abhishek G](mailto:abhishekabu0155@gmail.com).


