# FastAPI-BasicApplicatioon
Basic Operations API is a lightweight FastAPI-based REST API for addition, multiplication, and check operations via public GET endpoints. Admin-only logs are JWT-secured. Test interactively at /docs. Built with Python, FastAPI, and Uvicorn for a simple, secure API setup.

# Features
## Public Endpoints
1) GET /add?a=<int>&b=<int>: Adds two integers and returns the result.
2) GET /multiply?a=<int>&b=<int>: Multiplies two integers and returns the result.
3) GET /check?value=<value>: Performs a custom check operation (implementation-specific).

## Admin Endpoint
1) GET /logs: Retrieves API usage logs (requires JWT authentication).

## Authentication Endpoint
1) POST /token: Generates a JWT token for admin access to logs (username: admin, password: admin123).
2) Interactive Testing: Use Swagger UI at http://localhost:8000/docs to test endpoints.


# Process to Run the API
1) Clone the Repo
2) Open the Project in the IDE
3) Install the Requirements.txt
4) run the terminal with the following cmd: **uvicorn main:app --reload**
