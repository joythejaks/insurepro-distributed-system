# InsurePro Distributed System

Enterprise-grade distributed insurance quotation system.

This project demonstrates a production-style microservices architecture with event-driven communication.

---

## 🏗 Architecture Overview

Services:

- Auth Service
- User Service
- Quotation Service
- Notification Service
- API Gateway

Infrastructure:

- PostgreSQL (Database per service)
- NATS (Event Bus)
- Dockerized Environment

---

## 🔥 Architecture Principles

- Database isolation per service
- Event-driven communication
- Stateless services
- Independent deployability
- Clean service boundaries
- Environment-based configuration

---

## 🧠 Tech Stack

Backend:

- Go (Gin)
- PostgreSQL
- NATS

Frontend:

- React + TypeScript (Planned)

Infrastructure:

- Docker
- Docker Compose

---

## 🚀 Roadmap

- [ ] Infrastructure setup
- [ ] Auth Service
- [ ] Event publishing
- [ ] User Service consumer
- [ ] Quotation workflow
- [ ] Notification Service
- [ ] API Gateway
- [ ] Observability
