# NASA API

Welcome to the NASA API project! This project is designed to utilize SpaceX's REST API to display all of SpaceX's launch history. It's a Node.js application that serves as a backend service, fetching and processing data from SpaceX's API and presenting it in a structured format.

## Features

- Fetch and display SpaceX's launch history.
- REST API endpoints to query launch data.
- Integration with MongoDB for data persistence.
- Docker support for easy deployment.

## Technologies

This project is built using Node.js and Express, with a MongoDB database for storing launch history data. Here are the main technologies and libraries used:

- **Node.js & Express**: For setting up the server and API endpoints.
- **MongoDB & Mongoose**: For database management and schema definition.
- **Axios**: For making HTTP requests to SpaceX's API.
- **Cors**: To enable CORS with various options.
- **CSV-Parse**: For parsing CSV files, if needed.
- **Dotenv**: To load environment variables from a .env file.
- **Morgan**: HTTP request logger middleware for Node.js.
- **PM2**: Advanced, production process manager for Node.js.

### Development Dependencies

- **Jest**: For running tests.
- **Nodemon**: For automatically restarting the node application when file changes in the directory are detected.
- **Supertest**: For HTTP assertions, making it easy to test API endpoints.
