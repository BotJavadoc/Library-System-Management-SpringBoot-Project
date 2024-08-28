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
- [License](#license)
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
- **Database**: MySQL
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

    - Open your browser and go to `http://localhost:8080`.

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
![Login Page](./login%20page.png)

### Authentication Page
![Authentication Page](./auth%20page.png)

### Add Book
![Add Book](./add%20book.png)

### Admin Dashboard
![Admin Dashboard](./add%20auth.png)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.


## Contact

For any inquiries, please contact [yourname](mailto:abhishekabu0155@gmail.com).

---

Replace placeholders like "yourusername", "yourname", and "your.email@example.com" with your actual GitHub username, name, and email. Also, you might want to upload the screenshots to GitHub or another hosting service and update the links accordingly.
