# Multivendor Ecommerce Website with Laravel

Welcome to our multivendor ecommerce website built with Laravel. This application allows multiple vendors to sell their products on a single platform, providing a seamless shopping experience for users.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your machine:

- PHP (>= 8.1)
- Composer
- Node.js and npm
- Laravel CLI

### Installation

1. Clone the repository:

   `git clone https://github.com/IamMohiul/multi-ecommerce.git`

2. Navigate to the project directory:

   `cd multi-ecommerce`

3. Install PHP dependencies:

   `composer install`

4. Install JavaScript dependencies:

   `npm install`

5. Copy the example environment file and configure your database:

   `cp .env.example .env`

   Update the `.env` file with your database credentials.

6. Generate application key:

   `php artisan key:generate`

7. Run migrations and seed the database:

   `php artisan migrate --seed`

8. Start the development server:

   `php artisan serve`

   The application will be accessible at `http://localhost:8000`.

## Usage

Describe how to use your application. Include any important steps or information that users or developers should be aware of.

## Contributing

If you'd like to contribute to the project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Mention any libraries or resources that you used or were inspired by.

## Contact

- Mohiul Alam - immohiul@gmail.com

Feel free to reach out if you have any questions or feedback!
