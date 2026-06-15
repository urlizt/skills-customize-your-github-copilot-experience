# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a RESTful API using FastAPI and Pydantic. Students will create endpoints for listing, creating, and retrieving items while using automatic API documentation.

## 📝 Tasks

### 🛠️ Set up the API and define models

#### Description
Create a FastAPI application, define a Pydantic data model for items, and add an endpoint that returns a list of sample items.

#### Requirements
Completed program should:

- Import `FastAPI`, `HTTPException`, and `BaseModel`
- Define a Pydantic model named `Item` with `id`, `name`, `description`, and `price`
- Create a FastAPI app instance
- Add a `GET /items/` endpoint that returns a list of items

### 🛠️ Build CRUD endpoints and validation

#### Description
Add REST endpoints to create new items and retrieve items by ID. Use request validation and proper HTTP response codes.

#### Requirements
Completed program should:

- Add a `POST /items/` endpoint to accept item data and return the created item
- Add a `GET /items/{item_id}` endpoint to return a single item by ID
- Validate incoming requests using the `Item` model
- Return `404` when an item is not found
- Confirm the API documentation is available at `/docs` or `/redoc`
