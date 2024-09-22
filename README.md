# Cypress API Testing - ReqRes API

This repository contains a comprehensive suite of API tests using Cypress, designed to validate various endpoints of the ReqRes API. The tests cover user and resource management functionalities, including retrieval, creation, update, and deletion operations.

## Installation

```bash
git clone https://github.com/srajankumar/testing-reqres.git
cd testing-reqres
npm install
```

## Usage

```bash
npx cypress open
```

## Test Cases

The following test cases are included in the suite:

1. **Retrieve a list of users**: Validates the retrieval of all users.
2. **Retrieve a single user by ID**: Tests fetching a user by a valid ID.
3. **Retrieve single user with invalid ID**: Ensures that a 404 error is returned for a non-existent user.
4. **Retrieve a list of resources**: Checks the retrieval of all resources.
5. **Retrieve a single resource by ID**: Tests fetching a resource by a valid ID.
6. **Retrieve single resource with invalid ID**: Ensures a 404 error for a non-existent resource.
7. **Create a new user**: Validates the creation of a new user.
8. **Update user data with PUT**: Tests updating a user's data using the PUT method.
9. **Update user data with PATCH**: Tests partial updates on user data.
10. **Delete a user**: Validates successful deletion of a user.
11. **Register a new user - Successful**: Tests successful user registration.
12. **Register a new user - Unsuccessful**: Ensures correct error handling for registration without a password.
13. **Login - Successful**: Tests successful user login.
14. **Login - Unsuccessful**: Ensures correct error handling for login without a password.
15. **Delayed Response**: Validates handling of delayed responses from the API.
