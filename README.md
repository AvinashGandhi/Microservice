**GitHub Repository Description**

A containerized MEAN Stack microservices application built with Angular 19, Node.js, Express.js, and MongoDB. Features an API Gateway with Customer, Order, and Product services, RabbitMQ messaging integration, and Docker Compose for containerized deployment.

**README Introduction**

# MEAN Stack Microservices Application

This project demonstrates a microservices-based web application built using the MEAN stack and Docker.

## Features

- **Angular 19 Frontend:** User interface for interacting with the application.
- **API Gateway:** Central entry point that routes requests to backend microservices.
- **Customer Service:** Manages customer-related operations and data.
- **Product Service:** Handles product-related operations and data.
- **Order Service:** Manages order-related operations and integrates with RabbitMQ messaging.
- **MongoDB:** Database persistence using Mongoose.
- **RabbitMQ:** Message broker integration for asynchronous communication.
- **Docker:** Individual Docker images for the frontend and backend services.
- **Docker Compose:** Simplifies starting and managing the application containers.
- **Cloudflare Quick Tunnel:** Enables temporary public access for demonstrations and testing.

## Technology Stack

**Frontend:** Angular 19, TypeScript, Bootstrap

**Backend:** Node.js, Express.js

**Database:** MongoDB, Mongoose

**Messaging:** RabbitMQ, amqplib

**Containerization and Networking:** Docker, Docker Compose, Nginx

## Architecture

The Angular frontend communicates with the API Gateway, which routes requests to the Customer, Product, and Order microservices. The backend services use MongoDB for data persistence, while RabbitMQ supports messaging integration for order-related operations.

## Project Goal

The goal of this project is to explore microservices architecture, service-to-service communication, API Gateway routing, containerization, and application deployment using Docker.
