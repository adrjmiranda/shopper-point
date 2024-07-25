# Shopper Point

Shopper Point is an online store website developed in PHP. This project aims to demonstrate my web development skills and serve as an example for my developer portfolio.

## Functionalities

- Product Management: Add, edit and delete products.
- Shopping Cart: Add and remove products from the cart.
- Checkout: Checkout process with insertion of customer data.
- Authentication System: Login and user registration.
- Administrative Panel: Complete management of products, orders and users.

## Technologies Used

- Language: PHP
- Database: MySQL
- Front-end: HTML, CSS, JavaScript

## Libraries and Frameworks:

- Bootstrap (for styling)
- jQuery (for interactions)
- Slim Framework (for routing)
- Alpine.js (for interactive components)

## Requirements

    PHP 8.0+
    MySQL 5.7+
    Composer 2.0+

## Installation

1. Clone the repository:

```
git clone https://github.com/adrjmiranda/shopper-point.git
```

2. Navigate to the project directory:

```
cd shopper point
```

3. Install Composer dependencies:

```
composer install
```

4. Configure the .env file with your database credentials.

5. Run the database migrations:

```
php bin/console migrations:migrate
```

6. Start the development server:

```
php -S localhost:8000 -t public
```

7. Access the project at http://localhost:8000.

## Contribution

Contributions are welcome! Feel free to open issues or send pull requests.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.
