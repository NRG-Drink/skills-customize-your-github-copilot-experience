# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Students will build a small REST API using the FastAPI framework. They will define endpoints, use Pydantic models for validation, and run the app with Uvicorn.

## 📝 Tasks

### 🛠️	Create a basic REST API

#### Description
Create a FastAPI application that exposes endpoints to create, read, update, and delete simple "items". Use Pydantic models for request and response validation.

#### Requirements
Completed program should:

- Define a Pydantic model `Item` with fields `id: int`, `name: str`, and `price: float`.
- Implement endpoints: `GET /items`, `GET /items/{id}`, `POST /items`, `PUT /items/{id}`, `DELETE /items/{id}`.
- Use in-memory storage (a dictionary) for items. Keep it simple — persistence is optional.


### 🛠️	Add validation and auto-generated docs

#### Description
Add request validation and demonstrate the built-in API interactive docs provided by FastAPI.

#### Requirements
Completed program should:

- Validate incoming `POST` and `PUT` bodies using Pydantic and return proper HTTP status codes for errors.
- Show that the interactive Swagger UI is available at `/docs` and ReDoc at `/redoc`.


### 🛠️	Bonus: Simple persistence (optional)

#### Description
As a bonus, add lightweight persistence using SQLite with `databases` or `sqlite3`, or export/import JSON to a file.

#### Requirements

- On success, store items to disk (e.g., `items.json`) or use SQLite to persist between restarts.
- Provide setup/run instructions in the README.


## Running the starter code

1. Create a virtual environment and install dependencies: `pip install -r requirements.txt`
2. Run the app with Uvicorn: `uvicorn starter-code:app --reload`
3. Open `http://127.0.0.1:8000/docs` to explore the API.


## Deliverables

- A working FastAPI app in `starter-code.py`.
- A short explanation in the README of how to run and test the endpoints.
