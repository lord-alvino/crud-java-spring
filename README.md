# Simple CRUD
This repository contains a simple CRUD project built using Java Spring. The aim of this repository is to practice and share how you can build all CRUD Methods using Java Spring.

This project is built over an existing one created in a live (https://www.youtube.com/watch?v=tP6wtEaCnSI).

1. Start the application with Maven
2. The API will be accessible at http://localhost:8080

## API Endpoints
The API provides the following endpoints:

```markdown
GET /product - Retrieve a list of all data.

POST /product - Register a new data.

PUT /product - Alter data.

DELETE /product/{id} - Inactivate data.
```

## Database
The project uses PostgresSQL as the database. The necessary database migrations are managed using Flyway.

To install PostgresSQL locally you can [click here](https://www.postgresql.org/download/).