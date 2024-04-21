# Shapy

Shappy - Beauty with imperfections

## Description

Shappy is a project aimed at celebrating the unique beauty found in imperfect fruits and vegetables. It's built on Docker with services for WordPress, MySQL, and PHPMyAdmin.

## Features

- **Diverse Selection:** Explore a wide range of atypical fruits and vegetables, each with its own story.
- **Local Sourcing:** Products are sourced locally from passionate farmers.
- **Culinary Harmony:** Aims to create a culinary symphony where taste and sustainability meet.
- **Community Support:** Supports local farmers and promotes sustainable consumption.

## Project Setup

To run Shappy locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/shappy.git
    cd shappy
    ```

2. Start the Docker containers:
    ```bash
    docker-compose up -d
    ```

3. Access the WordPress site at [http://localhost:8080](http://localhost:8080) and set up your admin account.

4. Access PHPMyAdmin at [http://localhost](http://localhost) to manage the MySQL database.

## Docker Compose Configuration

### Services

- **wordpress:** WordPress application container.
- **db:** MySQL database container.
- **phpmyadmin:** PHPMyAdmin container for database management.

### Environment Variables

- **DB_HOST:** MySQL database host.
- **DB_USER:** MySQL database user.
- **DB_PASSWORD:** MySQL database password.
- **DB_NAME:** WordPress database name.
- **DB_ROOT_PASSWORD:** MySQL root password.

### Volumes

- **wordpress:** WordPress files.
- **db:** MySQL database files.

## Usage

Once the containers are running, visit [http://localhost:8080](http://localhost:8080) in your browser to access the Shappy WordPress site. You can customize the content and design to suit your needs.

## Contributors

- Gerad Mibe [@mibegerard](https://github.com/mibegerard)
