# E-commerce Microservices Project

## 📌 Description

This is a fully functional e-commerce application built using a microservices architecture. The project is designed to provide a scalable, secure, and high-performance online store. It includes features such as:

- User authentication and authorization
- Product catalog management
- Shopping cart functionality
- Payment integration
- API Gateway for service routing

## 🛠 Technologies Used

### Backend:

- **Spring Boot** - Core framework for microservices
- **Spring Cloud Gateway** - API Gateway for routing
- **Spring Security** - Authentication and authorization
- **Spring Data JPA** - Data access layer
- **PostgreSQL** - Relational database management

### Frontend:

- **Angular** - Modern frontend framework for building UI

### DevOps & Infrastructure:

- **Docker** - Containerization of services

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Docker & Docker Compose

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/wubbzy25/ecommerce.git
   cd ecommerce
   ```
2. Build and start the services using Docker Compose:
   ```bash
   docker-compose up --build -d
   ```
3. Access the application:

   - Backend API: `http://localhost:8000`
   - Frontend UI: `http://localhost:4200`

4. To stop the services:
   ```bash
   docker-compose down
   ```

## 🎥 Video Demo

https://github.com/user-attachments/assets/5b0889f1-37df-4994-a0bb-61383d3e694f

## 📄 License

This project is licensed under the MIT License.
