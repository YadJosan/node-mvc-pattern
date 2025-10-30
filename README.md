# MVC Pattern Project

A Node.js web application built using the Model-View-Controller (MVC) architectural pattern.

## Project Structure

```
mvc/
├── controllers/     # Request handlers and business logic
├── models/         # Database schemas and data models
├── node_modules/   # Project dependencies
├── public/         # Static assets (CSS, JS, images)
├── routes/         # Application route definitions
├── views/          # EJS templates for rendering HTML
├── app.js          # Application entry point
└── package.json    # Project configuration and dependencies
```

## Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB with Mongoose ODM
- **Template Engine**: EJS (Embedded JavaScript)
- **Dev Tool**: Nodemon for auto-reloading

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

Start the development server with auto-reload:
```bash
npm run dev
```

The application will run on the default Express port (typically `http://localhost:8000`).

## MVC Architecture

- **Models**: Define data structure and interact with MongoDB
- **Views**: EJS templates that render the user interface
- **Controllers**: Handle HTTP requests, process data, and return responses
- **Routes**: Map URLs to controller functions

## Development

The project uses Nodemon in development mode, which automatically restarts the server when file changes are detected.
