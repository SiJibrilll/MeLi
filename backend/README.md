
# meli-be

**meli-be** is a Laravel-based backend application designed to serve as the backend for your application. It includes RESTful API endpoints, user authentication, and other backend features built with Laravel.

## Features

- Laravel 12
- RESTful API endpoints
- Authentication using Laravel Sanctum
- Role-based access control
- Database migrations and seeders

## Prerequisites

Make sure you have the following installed on your machine:

- PHP >= 8.1
- Composer
- Node.js and npm
- MySQL or PostgreSQL
- Git

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/SiJibrilll/meli-be.git
cd meli-be
composer install
npm install
cp .env.example .env
php artisan key:generate
```

Configure your `.env` file with your database credentials and other environment-specific settings.

Then, run migrations and seed the database:

```bash
php artisan migrate --seed
```

Finally, start the local development server:

```bash
php artisan serve
```

Your app should now be running at `http://localhost:8000`.

## Usage

- **API Endpoint Base URL:** `http://localhost:8000/api`
- **Authentication:** Laravel Sanctum is used for API authentication. Use bearer tokens or session cookies as required.

## Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add my feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Made with ❤️ by [@SiJibrilll](https://github.com/SiJibrilll)
