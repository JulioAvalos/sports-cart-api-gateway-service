# Sports Cart API Gateway

This is the API Gateway service for the Sports Cart application.  
It routes requests to backend microservices (user, product, and order services) and handles cross-cutting concerns like CORS and JWT authentication.

## Features

- Centralized routing to all backend services
- JWT-based request validation
- Global CORS configuration
- Built with Spring Cloud Gateway

## Base URL
> http://localhost:8080


## Routed Paths

| Path                  | Service           |
|-----------------------|-------------------|
| `/api/auth/**`        | user-service      |
| `/api/users/**`       | user-service      |
| `/api/products/**`    | product-service   |
| `/api/order/**`       | order-service     |
