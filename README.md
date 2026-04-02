# inventorymaster-1

> InventoryMaster 1: Warehouse management with barcode scanning and forecasting

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Ruby, Rails, MySQL, Redis, Active Job

## 🏗️ Architecture
Three-tier architecture: Ruby, Rails backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/inventorymaster-1
cd inventorymaster-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
