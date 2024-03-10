# Task Manager with Authentication

This project is a comprehensive task management system that includes robust authentication features. Designed to help teams and individuals organize, track, and manage their tasks efficiently, our system provides a secure environment where users can manage their workloads with ease.

## Features

- **User Authentication:** Secure login and registration system to keep your account protected.
- **Task Management:** Create, update, view, and delete tasks with simple, user-friendly interfaces.
- **Roles and Permissions:** Different access levels for admins and regular users to ensure proper task management and system administration.
- **Deleted Tasks Retrieval:** Special feature for admins to view and manage deleted tasks, allowing for data recovery and audit trails.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What you need to install the software:

- PHP >= 7.3
- Composer
- Laravel >= 8.x
- MySQL or any preferred database system

### Installation

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/task-manager-with-auth.git
    ```

2. Navigate into the project directory:
    ```sh
    cd task-manager-with-auth
    ```

3. Install dependencies:
    ```sh
    composer install
    ```

4. Copy the example env file and make the required configuration changes in the `.env` file:
    ```sh
    cp .env.example .env
    ```

5. Generate an application key:
    ```sh
    php artisan key:generate
    ```

6. Run the migration and seed the database (make sure your database configuration is correct in `.env`):
    ```sh
    php artisan migrate --seed
    ```

7. Start the local development server:
    ```sh
    php artisan serve
    ```
    The application will be available at `http://localhost:8000`.

## API Endpoints

Refer to the detailed API documentation sections in Insomnia on the available endpoints, including how to authenticate, create, manage, and delete tasks.

