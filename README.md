# ecommerce-api-node

# E-commerce API

This is a RESTful API for an e-commerce system. It provides endpoints to manage products, their variants, and also search functionality.

## Features

- Create, read, update, and delete products
- Manage product variants
- Search for products by name, description, or variant name

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- Joi for input validation

## Getting Started

### Prerequisites

- Node.js and npm should be installed on your machine
- MongoDB should be installed and running

### Installation

1. Clone the repository:

   
   git clone https://github.com/AfridiSoftwareAce/ecommerce-api-node.git
### Install dependencies:
npm install

### Configuration
Create a .env file in the root directory.

### Set the following environment variables in the .env file:
PORT=8000
MONGODB_URI=<your-mongodb-uri>
Usage

### Start the server:
nodemon server.js

The API will be available at http://localhost:8000

### API Endpoints
POST /products - Create a new product
GET /products - Get all products
GET /products/:id - Get a specific product
PUT /products/:id - Update a specific product
DELETE /products/:id - Delete a specific product
GET /products/search - Search for products by name, description, or variant name

### Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

### Contact
For any inquiries, please contact Afridi Wara at afridiwara@ymail.com.


Remember to replace `<your-mongodb-uri>` in the `.env` file section with your actual MongoDB URI. The same goes for the repository URL in the Installation section.

