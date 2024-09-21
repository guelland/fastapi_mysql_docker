# FastAPI MySQL Docker

This project provides a sample application that integrates FastAPI with MySQL in a Docker container.

## Table of Contents

- Installation
- Usage
- Project Structure
- Configuration
- Contributing
- License

## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/integration-developer-  de/fastapi_mysql_docker.git
cd fastapi_mysql_docker
```
2. **Start the Docker container**
```bash
docker-compose up --build
```
3. **Usage**
After starting the Docker container, the application will be accessible at http://localhost:8000

API Testing
You can test the API using Postman or any other API client.

Open your browser and go to:
API Root: http://localhost:8000
Swagger Documentation: http://localhost:8000/docs/v1
Redoc Documentation: http://localhost:8000/redoc/v1

Using Postman:
Import the API collection: You can manually create requests in Postman or import an existing collection if available.
Create a new request: Set the method (GET, POST, etc.) and the URL (e.g., http://localhost:8000/...).
Send the request: View the response and test different endpoints as needed

4. **Project Structure**
fastapi_mysql_docker/
├── app/
│   ├── main.py
│   ├── models.py
│   ├── schemas.py
│   ├── crud.py
│   └── database.py
├── docker-compose.yml
├── Dockerfile
└── README.md

## Author

Created by integration-developer.de

## License

This project is licensed under the [Feel free to experiment] license.
