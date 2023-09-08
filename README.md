# Tbay Project

## Introduction

Tbay Project is a web application built using Laravel 10 and Bootstrap 5 to create a basic authentication system. This README file provides an overview of the project, its purpose, and instructions for setting it up.

## Table of Contents

- [Requirements]
- [Installation]
- [Usage]
- [Contributing]
- [License]

## Requirements

Before you begin, ensure you have met the following requirements:

- [Composer](https://getcomposer.org/download/) installed.
- [PHP](https://www.php.net/downloads) 8.1 or higher.
- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/get-npm) for managing frontend assets.
- A web server (e.g., Apache, Nginx) with PHP support.

## Installation

Follow these steps to set up the Tbay Project on your local machine:

1. Clone the repository:

   git clone https://github.com/reenasharma89/tbay-project.git

2. Change to the project directory:

   cd tbay-project

3. Install PHP dependencies using Composer:

   composer install

4. Install JavaScript dependencies using npm:

   npm install

5. Create a `.env` file by copying the example:

   cp .env.example .env

6. Generate an application key:

   php artisan key:generate

7. Configure your database settings in the `.env` file.

8. Migrate the database:

   php artisan migrate

9. Seed the database (optional):

   php artisan db:seed

10. Start the development server:

    php artisan serve

11. Visit `http://localhost:8000` in your web browser to access the application.

## Usage

Tbay Project is a basic authentication system created using Laravel 10 and Bootstrap 5. It provides user registration, login, and password reset functionalities out of the box. You can customize and extend it to suit your specific project requirements.

## Contributing

Contributions are welcome! If you want to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to the main repository's `main` branch.

Please ensure your code follows the project's coding standards and includes appropriate tests if applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using Tbay Project! If you have any questions or encounter any issues, please feel free to [open an issue](https://github.com/your-username/tbay-project/issues).