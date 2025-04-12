# Ecommerce_app_ruby

A full-featured e-commerce web application built with Ruby on Rails, designed to provide a seamless online shopping experience.

## Features

- **User Authentication**: Secure sign-up, login, and session management.
- **Product Management**: CRUD operations for products with categories and images.
- **Shopping Cart**: Add, update, and remove items from the cart.
- **Order Processing**: Checkout process with order summary and confirmation.
- **Admin Dashboard**: Manage products, orders, and users.
- **Responsive Design**: Mobile-friendly interface for a better user experience.

## Technologies Used

- **Backend**: Ruby on Rails
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (development), PostgreSQL (production)
- **Authentication**: Devise gem
- **Payment Integration**: Stripe API
- **Deployment**: Docker, Render

## Getting Started

### Prerequisites

- Ruby 3.x
- Rails 7.x
- Bundler
- Node.js & Yarn
- Docker (optional, for containerized deployment)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Shubhamdev9229/Ecommerce_app_ruby.git
   cd Ecommerce_app_ruby
   ```

2. **Install dependencies**:

   ```bash
   bundle install
   yarn install
   ```

3. **Set up the database**:

   ```bash
   rails db:create
   rails db:migrate
   rails db:seed
   ```

4. **Start the Rails server**:

   ```bash
   rails server
   ```

   Visit `http://localhost:3000` in your browser to access the application.

## Deployment

This application includes a `Dockerfile` and `render.yaml` for deployment on platforms like Render.

### Using Docker

1. **Build the Docker image**:

   ```bash
   docker build -t ecommerce_app .
   ```

2. **Run the Docker container**:

   ```bash
   docker run -p 3000:3000 ecommerce_app
   ```

### Deploying to Render

Ensure you have a Render account and follow their documentation to deploy using the provided `render.yaml` configuration.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

