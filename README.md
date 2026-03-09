<div align="center">

# CRUDIFY - v1.1.0

**Minimal RESTful CRUD API built with FastAPI**

Simple • Containerized • Developer-friendly • GitOps

</div>

---

## Overview

**CRUDIFY** is a lightweight RESTful API implementing basic **Create, Read, Update, Delete (CRUD)** operations using *
*FastAPI**.

The project focuses on demonstrating:

* RESTful API design
* FastAPI fundamentals
* structured backend development
* containerized environments using Docker
* Introduced CI/CD pipeling

The codebase is intentionally minimal and easy to extend.

---

# Features

* Create records
* Retrieve records
* Update records
* Delete records
* Input validation with Pydantic
* Structured error handling
* Docker containerization
* Docker Compose orchestration
* CI/CD pipeline

---

# Tech Stack

| Layer             | Technology     |
|-------------------|----------------|
| Backend Framework | FastAPI        |
| Server            | Uvicorn        |
| Validation        | Pydantic       |
| Containerization  | Docker         |
| Orchestration     | Docker Compose |
| API Testing       | Postman        |
| CI/CD             | GitHub Actions |

---

# Running with Docker (Recommended)

Build and start the containers:

```bash
docker-compose up --build
```

The API will be available at:

```
http://0.0.0.0:8000
```

---

# Running Locally

Install dependencies:

```bash
pip install --no-cache-dir -r requirements.txt
```

Start the development server:

```bash
uvicorn main:app --reload --port 8000
```

---

# API Documentation

FastAPI automatically generates interactive documentation.

Swagger UI

```
http://0.0.0.0:8000/docs
```

ReDoc

```
http://0.0.0.0:8000/redoc
```

---

# Future Improvements

- Pagination & filtering 🔃
- Rate limiting 🔃
- Caching layer ✅
- Unit & integration testing ✅
- Dockerization ✅
- CI/CD pipeline ✅

---

<div align="center">


*Thank you* ❤️

</div>