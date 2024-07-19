# E-commerce Backend

This is a Node.js backend for an e-commerce application using Express and MongoDB.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js, npm, and MongoDB installed on your local machine.

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)

### Installing

1. Clone the repository:
   ```bash
   git clone https://github.com/coderooz/ecommerce-backend.git
   cd ecommerce-backend
   ```

2. Install the dependencies:
   ```bash
    npm install express mongoose body-parser bcryptjs jsonwebtoken
   ```

3. Start MongoDB:
   ```bash
   mongod
   ```

4. Start the server:
   ```bash
   node index.js
   ```

5. The API will be available at `http://localhost:3000`.

### API Endpoints

- `POST /api/register` - Register a new user
- `POST /api/login` - Login a user and get a token
- `GET /api/products` - Retrieve all products
- `POST /api/products` - Create a new product (protected)

### Built With

- [Express](https://expressjs.com/) - The web framework used
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling tool
- [Body-parser](https://www.npmjs.com/package/body-parser) - Node.js body parsing middleware
- [Bcryptjs](https://www.npmjs.com/package/bcryptjs) - Library to hash passwords
- [Jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - Library to sign and verify tokens

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Authors

- **Ranit Saha** - *Initial work* - [Coderooz](https://github.com/coderooz)

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
---