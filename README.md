# QuantaStock Product Management Website - README

Welcome to the documentation for QuantaStock, a web application built using React for the front-end, Spring Boot for the back-end, and MySQL for the database. This application allows users to perform CRUD (Create, Read, Update, Delete) operations on product data.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Database](#database)
- [Contributing](#contributing)
- [License](#license)

## Introduction

QuantaStock is designed to help businesses efficiently manage their product inventory. It provides a user-friendly interface for performing various operations on product data, such as adding new products, updating existing products, viewing product details, and deleting products.

## Features

- User-friendly web interface
- Create new products with details
- View a list of all products
- Update product information
- Delete products from the inventory

## Technologies Used

- **Front-end**: React (React Hook, React Router 6.0 )
- **Back-end**: Spring Boot ,Rest Api
- **Database**: MySQL
- **Server** : Apache Tomcat Server
- **Tools** : STS, Vscode
## Screenshots

_Include screenshots of your website pages here_
<p float="left">
<img src="https://github.com/Aditya-Kumar-Dwivedi/QuantaStock/blob/main/Product-Management/src/images/Pic%201.png" alt="drawing" width="500" height="500">
<img src="https://github.com/Aditya-Kumar-Dwivedi/QuantaStock/blob/main/Product-Management/src/images/Pic%202.png" alt="drawing" width="500" height="500">
<img src="https://github.com/Aditya-Kumar-Dwivedi/QuantaStock/blob/main/Product-Management/src/images/Pic%203.png" alt="drawing" width="500" height="500">

</p>
## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js
- Java Development Kit (JDK)
- MySQL server

### Installation

1. Clone this repository to your local machine.
2. Navigate to the `frontend` directory and run the following commands:

   ```
   npm install
   npm start
   ```
3.Open another terminal window, navigate to the backend directory and run the Spring Boot application:
```
./mvnw spring-boot:run
```
## Usage

1. Open your web browser and access the application by entering `http://localhost:3000` in the address bar.
2. You'll land on the product list page where you can view all products.
3. Use the navigation options to add new products, update existing ones, and delete products.

## API Endpoints

The Spring Boot back-end provides the following API endpoints:

- `GET /api/products`: Fetch a list of all products.
- `GET /api/products/{id}`: Fetch details of a specific product.
- `POST /api/products`: Create a new product.
- `PUT /api/products/{id}`: Update product details.
- `DELETE /api/products/{id}`: Delete a product.

## Database

The application uses MySQL to store product data. The database schema includes a `products` table with fields such as `id`, `name`, `description`, `price`, etc.

## Contributing

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and test thoroughly.
4. Submit a pull request explaining the changes you've made.



