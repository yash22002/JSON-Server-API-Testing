# JSON Server API Testing

## Project Overview
This project focuses on API testing using Postman and JSON Server. A mock REST API was created using a local JSON file to practice CRUD operations.

## Tools & Technologies
- Postman
- JSON Server
- Node.js
- JavaScript
- Git & GitHub

## API Testing Scope
- GET – Retrieve employee records
- POST – Create a new employee
- PUT – Update complete employee details
- PATCH – Update partial employee details
- DELETE – Delete employee records
- HEAD – Check response headers
- OPTIONS – Check supported HTTP methods

## Test Scenarios
- Positive Testing
- Negative Testing
- Status Code Validation
- Response Body Validation
- CRUD Operations

## API Endpoint
`http://localhost:3000/Company`

## How to Run
1. Install Node.js.
2. Install JSON Server:
   `npm install -g json-server`
3. Start the server:
   `npx json-server Employee.json --port 3000`
4. Import the Postman collection.
5. Execute the API requests.

## Note
This project uses a local mock API server. The API endpoint is accessible only while the local server is running.
