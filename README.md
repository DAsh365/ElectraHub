# ElectraHub

## Description
This project is a backend application for an e-commerce website. It uses Node.js, Express.js, and Sequelize ORM to handle server-side operations such as database management and API routes.

## Installation
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.

## Demo Video

To demonstrate the functionality of the e-commerce back end, please watch the following walkthrough video:

[Watch Demo Video](https://drive.google.com/file/d/1y1IQbro8ycaVZN3CYowyhPXxZyI5R6BJ/view?usp=sharing)

## Usage
1. Set up your MySQL database and configure the connection settings in the `.env` file.
2. Run the database schema and seed data using `npm run seed`.
3. Start the server using `npm start`.
4. Use an HTTP client like Insomnia or Postman to interact with the API endpoints.

## API Endpoints
- `GET /api/categories`: Get all categories.
- `GET /api/categories/:id`: Get a single category by ID.
- `POST /api/categories`: Create a new category.
- `PUT /api/categories/:id`: Update a category by ID.
- `DELETE /api/categories/:id`: Delete a category by ID.

- `GET /api/products`: Get all products.
- `GET /api/products/:id`: Get a single product by ID.
- `POST /api/products`: Create a new product.
- `PUT /api/products/:id`: Update a product by ID.
- `DELETE /api/products/:id`: Delete a product by ID.

- `GET /api/tags`: Get all tags.
- `GET /api/tags/:id`: Get a single tag by ID.
- `POST /api/tags`: Create a new tag.
- `PUT /api/tags/:id`: Update a tag by ID.
- `DELETE /api/tags/:id`: Delete a tag by ID.

## Contributing
Contributions are welcome! If you find any issues or want to suggest improvements, please submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).