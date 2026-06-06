# Microservices Task

## Overview

This project demonstrates a microservices architecture using Node.js, Express.js, Docker, and Docker Compose.

### Services Included

* User Service
* Product Service
* Order Service
* Gateway Service

## Project Structure

```text
Microservices/
├── user-service
├── product-service
├── order-service
├── gateway-service
├── docker-compose.yml
└── README.md

screenshots/
├── 01-docker-compose-running.png
├── 02-docker-containers.png
├── 03-user-service-response.png
├── 04-product-service-response.png
├── 05-order-service-response.png
├── 06-gateway-users-response.png
├── 07-gateway-products-response.png
├── 08-gateway-orders-response.png
├── 09-dockerfiles.png
└── 10-docker-compose-file.png
```

## Docker Setup

### Build and Start Services

```bash
docker compose up --build
```

### Stop Services

```bash
docker compose down
```

## Service Endpoints

### User Service

**GET /users**

```text
http://localhost:3000/users
```

### Product Service

**GET /products**

```text
http://localhost:3001/products
```

### Order Service

**GET /orders**

```text
http://localhost:3002/orders
```

### Gateway Service

**GET /api/users**

```text
http://localhost:3003/api/users
```

**GET /api/products**

```text
http://localhost:3003/api/products
```

**GET /api/orders**

```text
http://localhost:3003/api/orders
```

## Screenshots

### Docker Compose Running

![Docker Compose Running](screenshots/01-docker-compose-running.png)

### Docker Containers

![Docker Containers](screenshots/02-docker-containers.png)

### User Service Response

![User Service Response](screenshots/03-user-service-response.png)

### Product Service Response

![Product Service Response](screenshots/04-product-service-response.png)

### Order Service Response

![Order Service Response](screenshots/05-order-service-response.png)

### Gateway Users Response

![Gateway Users Response](screenshots/06-gateway-users-response.png)

### Gateway Products Response

![Gateway Products Response](screenshots/07-gateway-products-response.png)

### Gateway Orders Response

![Gateway Orders Response](screenshots/08-gateway-orders-response.png)

### Dockerfiles

![Dockerfiles](screenshots/09-dockerfiles.png)

### Docker Compose File

![Docker Compose File](screenshots/10-docker-compose-file.png)

## Technologies Used

* Node.js
* Express.js
* Axios
* Docker
* Docker Compose

## Author

Vivek Pathak
