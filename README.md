Microservices Task
Overview
This project demonstrates a microservices architecture using Node.js, Express, Docker, and Docker Compose.
Services included:
· User Service
· Product Service
· Order Service
· Gateway Service
Project Structure
Microservices/
├── user-service
├── product-service
├── order-service
├── gateway-service
├── docker-compose.yml
└── README.md
Docker Setup
Build and start services:
docker compose up –build
Stop services:
docker compose down
Service Endpoints
User Service
GET /users
http://localhost:3000/users
Product Service
GET /products
http://localhost:3001/products
Order Service
GET /orders
http://localhost:3002/orders
Gateway Service
GET /api/users
GET /api/products
GET /api/orders
Screenshots
Docker Compose Running
  

  

Docker Containers
  

User Service Response
  

Product Service Response
  

Order Service Response
  

Gateway Users Response
  

Gateway Products Response
  

Gateway Orders Response 
  

Dockerfile 
  

docker-compose.yml
  

Technologies Used
· Node.js
· Express.js
· Axios
· Docker
· Docker Compose