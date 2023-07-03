# Student Management System

Student Management System is a web application built using the Laravel framework that allows teachers and administrators to manage students' academic records, including personal details, course enrollment, and grades.

## Technologies Used

- Laravel 8
- PHP 7.4
- MySQL
- Bootstrap 5
- JavaScript
- Ajax
- jQuery

## Features

- User Registration and Login
- Student Profile Management
- Enrollment Management

## Installation and Usage

To get started with the Student Management System, follow the instructions below:

1. Clone the repository, navigate to the project directory, and install the project dependencies using Composer:

    ```bash
    git clone <repository-url>
    cd student-management-system
    composer install
    ```

2. Rename the `.env.example` file to `.env`:

    ```bash
    mv .env.example .env
    ```

3. Update the database credentials in the `.env` file:

    ```bash
    DB_CONNECTION=mysql
    DB_HOST=your-host
    DB_PORT=your-port
    DB_DATABASE=your-database
    DB_USERNAME=your-username
    DB_PASSWORD=your-password
    ```

4. Generate an application key and create the necessary database tables:

    ```bash
    php artisan key:generate
    php artisan migrate
    ```

5. Start the development server:

    ```bash
    php artisan serve
    ```

6. Open your web browser and navigate to `http://localhost:8000` to access the Student Management System.

## Credits

This project makes use of the following open-source libraries and frameworks:

- Laravel Framework
- Bootstrap
- Font Awesome
- Undraw