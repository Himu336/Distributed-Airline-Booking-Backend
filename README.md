# ✈️ Distributed Airline Booking System
> A backend-engineered, microservices-driven airline booking system built with a distributed architecture, emphasizing asynchronous communication using RabbitMQ, API Gateway-based routing, ACID-compliant databases, and decoupled service orchestration for high scalability and fault tolerance.

## 🛠️ Overview
The **Distributed Airline Booking System** is a backend-centric project designed with a strong focus on **scalability**, **modularity**, and **clean service separation**. Inspired by real-world airline operations, it simulates the core backend infrastructure required for managing **flights**, **bookings**, **payments**, and **user operations** at scale.

This repository represents the **centralized entry point** of the system, outlining the overall structure and **orchestration** across multiple backend services.

### 🔑 Key Highlights (Table Format):

| Feature                               | Description                                                                                                                                                      |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Service-Oriented Architecture (SOA)**        | Clear separation of concerns across different domain-driven microservices.                                                                                         |
| **Scalable API Gateway with Authentication**   | Acts as the single entry point for all client interactions, handling routing, request validation, authentication, and rate limiting.                              |
| **Asynchronous Service Orchestration**        | Certain services interact via message queues (e.g., RabbitMQ) to coordinate workflows, reduce tight coupling, and improve resilience in multi-step operations.    |
| **ACID-Compliant Databases**                  | Ensures data consistency, integrity, and reliability across core services like bookings and payments.                                                             |
| **Scalable, Observable Infrastructure**       | Each microservice is designed to scale independently, with integrated observability (logs, metrics, traces) for real-time monitoring and debugging.               |

---

This system is engineered not just to function, but to mimic how **production-grade airline backend systems** are designed to handle **concurrent users**, ensure **high availability**, and provide **robust fault handling**.

## 📦 Repository and Service Links
This section maps out each core microservice and its corresponding repository.

| Service Name              | Description                            | Repository Link                                                |
|--------------------------|----------------------------------------|----------------------------------------------------------------|
| API Gateway              | Central entry point for all services; handles routing, auth, and rate limiting | [Airline-API-Gateway](https://github.com/Himu336/Airline-API-Gateway) |
| Flights Service          | Manages airports, airplanes, cities, and flight inventory with full CRUD support | [Airline-Flights-Service](https://github.com/Himu336/Airline-Flights-Service) |
| Booking Service          | Handles seat bookings, cancellations, and payment coordination | [Airline-Booking-Service](https://github.com/Himu336/Airline-Booking-Service) |
| Notification Service     | Sends booking confirmations and system alerts via email/SMS | [Airline-Notification-Service](https://github.com/Himu336/Airline-Notification-Service) |

## 🚀 Test My Backend
You can explore and test the complete flow of the airline booking system — from flight selection to booking confirmation and email notification — using the Postman collection below. This includes all available API endpoints across the microservices.

🔗 **Postman Collection:** [Insert your Postman link here]
