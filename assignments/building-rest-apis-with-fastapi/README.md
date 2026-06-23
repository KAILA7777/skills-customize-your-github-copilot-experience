# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a simple REST API with FastAPI by defining routes, handling requests, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create Your First FastAPI App

#### Description
Set up a basic FastAPI application and define a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Import FastAPI and create an app instance.
- Define a GET route at `/`.
- Return a JSON response with a welcome message.
- Run the app locally and confirm the route works.

### 🛠️ Build a Simple Item API

#### Description
Add endpoints for creating and reading items in a small in-memory collection.

#### Requirements
Completed program should:

- Define a GET endpoint to list items.
- Define a POST endpoint to add an item.
- Store items in a Python list or dictionary while the app is running.
- Return item data as JSON and include a unique identifier.

### 🛠️ Add Validation and Error Handling

#### Description
Improve the API by validating input and handling missing items gracefully.

#### Requirements
Completed program should:

- Use request models or simple validation for item data.
- Return a clear 404 response when an item is not found.
- Include helpful error messages for invalid requests.
