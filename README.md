# Back-End API for Login System

This is the back-end API for the login system project built with Laravel Breeze. It provides the necessary endpoints to support user authentication and integrate with the front-end application.

The front-end project repository can be found at [https://github.com/lanng/vue-front](https://github.com/lanng/vue-front).

## Technologies Used

- **Laravel Breeze**: A starter kit for Laravel that provides a simple and minimalistic authentication system.

## Project Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/login-system-api.git
   ```

2. Navigate to the project directory:

    ```bash
    cd api-laravel-breeze
    ```

3. Install the dependencies:

    ```bash
    composer install
    ```

4. Set up the environment:
    - Create a copy of the .env.example file and rename it to .env.
    - Update the necessary configurations such as database connection details in the .env file.

5. Generate the application key:

    ```bash
    php artisan key:generate
    ```

6. Run the database migrations:

    ```bash
    php artisan migrate
    ```

7. Start the development server:

    ```bash
    php artisan serve
    ```

8. Access the front-end application:

    Open your browser and visit the front-end application repository at [vue-front](https://github.com/lanng/vue-front) for instructions on setting up and running the Vue front-end application.

## API Endpoints

The back-end API provides the following endpoints:

- `/register` (POST): Register a new user.
- `/login` (POST): Log in with user credentials and receive an authentication token.
- `/logout` (POST): Log out the currently authenticated user.
- `/user` (GET): Retrieve the authenticated user's information.
- `/forgot-password` (POST): Send a password reset link to the user's email address.
- `/reset-password` (POST): Reset the user's password using a valid reset token.

Refer to the front-end application repository at [https://github.com/lanng/vue-front](https://github.com/lanng/vue-front) for details on how these endpoints are consumed and integrated with the front-end.

For more details and customization options, refer to the Laravel Breeze documentation at [Laravel Documentation](https://laravel.com/docs/8.x/starter-kits#laravel-breeze)
