# E-Commerce Backend

This project is a backend service for an e-commerce platform. It provides APIs for managing products, users, orders, and other essential functionalities for an online store.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install the necessary dependencies, run the following command:

```bash
npm install
```

## Usage

To start the server, use the following command:

```bash
npm start
```

By default, the server will run on port 3000. You can access the API at `http://localhost:3000`.

[Demo](<Screen Recording 2024-07-10 at 5.21.14 PM.mov>)

## Project Structure

The project structure is organized as follows:

```
E-Commerce-Backend/
├── config/          # Configuration files for the application
├── db/              # Database setup and migration files
├── models/          # Mongoose models for MongoDB collections
├── routes/          # Route handlers for API endpoints
├── seeds/           # Seed data for populating the database
├── .git/            # Git repository files
├── .DS_Store        # System file (can be ignored)
├── package.json     # NPM package configuration
├── server.js        # Entry point of the application
```

## Configuration

The configuration files are located in the `config` directory. You can set environment-specific variables in these files.

## Scripts

The following scripts are available:

- `npm start`: Starts the server.
- `npm test`: Runs the test suite (if available).

## Contributing

If you wish to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your branch.
4. Create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Created by

- Tristin Rohr
