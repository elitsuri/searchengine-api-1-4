# searchengine-api-1

> SearchEngine API 1: Full-text and vector search with faceting and relevance tuning

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Audit logging and activity history
- Background jobs for long-running workflows
- Admin analytics dashboard with operational metrics
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway
- Health checks, readiness checks, and structured logging
- Production-oriented environment configuration

## 🧰 Tech Stack
C, HTTP Server, SQLite, Makefile

## 🏗️ Architecture
Three-tier architecture: C, HTTP Server backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/searchengine-api-1
cd searchengine-api-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
