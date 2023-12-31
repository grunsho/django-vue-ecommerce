# Djackets Ecommerce Platform

This is a full-stack e-commerce platform built using Django Rest Framework (DRF), Vue.js, and Bulma.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is aimed at creating a modern e-commerce platform that leverages Django Rest Framework on the backend to provide robust API endpoints and Vue.js on the frontend for a seamless user experience. The UI is designed using Bulma CSS framework for a clean and responsive design.

## Features

- User authentication and authorization
- Product browsing, searching, and filtering
- Shopping cart functionality
- Checkout and payment processing integration
- Order management
- Admin dashboard for managing products, orders, and users

## Installation

To get started with the project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/e-commerce.git`
2. Navigate to the backend directory: `cd djackets_django`
3. Install Python dependencies: `pip install -r requirements.txt`
4. Apply database migrations: `python manage.py migrate`
5. Start the Django server: `python manage.py runserver`

For the frontend:

1. Navigate to the frontend directory: `cd djackets_vue`
2. Install Node.js dependencies: `npm install`
3. Start the Vue development server: `npm run serve`

## Usage

Once the installation is complete, you can access the application:

- Backend API: `http://localhost:8000/api/v1/`
- Frontend: `http://localhost:8080/`

Make sure to configure the environment variables, database settings, and API endpoints as needed for your deployment environment.

## Technologies Used

- Django Rest Framework
- Vue.js
- Bulma CSS Framework
- Axios for API requests

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the contribution guidelines.

## License

This project is licensed under the [MIT License](LICENSE).