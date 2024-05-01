# Microservices for E-Commerce Platform

## Introduction
This e-commerce microservices project was developed to deepen my understanding of modern, distributed system architectures. By implementing a set of interconnected services, I aimed to explore the core principles of microservices, including service discovery, inter-service communication, and distributed tracing. Through the use of technologies such as Eureka for service registration, OpenFeign for service-to-service communication, and Zipkin for end-to-end request tracing, this project serves as a learning platform to dive into the complexities of building and maintaining a robust, scalable, and resilient e-commerce application. 

## Service Repositories
- [Product Service](https://github.com/bryanyi/siramiks-ProductService)
- [Order Service](https://github.com/bryanyi/siramiks-OrderService)
- [Payment Service](https://github.com/bryanyi/siramiks-PaymentService)
- [Authentication Service](https://github.com/bryanyi/Siramiks-Auth-Service)
- [API Gateway](https://github.com/bryanyi/siramiks-ApiGateway)
- [Service Discovery](https://github.com/bryanyi/siramiks-ServiceDiscovery)

## Architecture
The project consists of the following services:
- Product Service: Responsible for managing product-related data, such as product information, inventory, and pricing.
- Order Service: Handles the creation, processing, and management of customer orders.
- User Service: Manages user accounts, authentication, and customer profiles.
- Payment Service: Processes customer payments and integrates with third-party payment gateways.
- Inventory Service: Tracks and updates the availability of products in the system.
- API Gateway: Serves as the entry point for client applications, providing a unified interface and handling cross-cutting concerns such as authentication, rate limiting, and load balancing.
- Service Registry (Eureka): Enables dynamic service discovery, allowing the microservices to locate and communicate with each other.
- Distributed Tracing (Zipkin): Provides end-to-end visibility into the flow of requests across the microservices, aiding in debugging and performance optimization.

## Technologies Used
- Spring Boot
- Spring Cloud
- Spring Security (JWT)
- Eureka 
- OpenFeign
- Zipkin (Distributed Tracing)
- Redis (Caching and Rate Limiting)
- Postgres
- Docker
- Stripe
