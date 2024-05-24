# django_datapeace
Backend Assignment Submission

# User Management API

This project implements a RESTful API for managing user data. Endpoints-
1. Listing users
2. Creating a new user
3. Updating user information
4. Deleting users

## Setup

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd user_management
    ```

3. Install dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

4. Run migrations to create the database schema:

    ```bash
    python manage.py migrate
    ```

## Usage

1. Start the Django development server:

    ```bash
    python manage.py runserver
    ```

2. Access the API endpoints using a tool like Postman or cURL:

    - List Users: `GET /api/users/`
    - Create User: `POST /api/users/`
    - Update User: `PUT /api/users/<id>/`
    - Delete User: `DELETE /api/users/<id>/`

## Project Structure

The project directory structure is organized as follows:

