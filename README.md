 Flask Microservices with Docker and NGINX

This project demonstrates a microservices architecture using two independent Flask services containerized with Docker, and routed through NGINX as a reverse proxy. The setup mirrors real-world backend deployment practices.

---

Features

- > Two Flask-based microservices (service1 and service2)
- > Dockerized using Docker and Docker Compose
- > NGINX reverse proxy for routing requests to the correct service
- > Isolated, scalable, and modular microservices structure
- > Perfect for learning backend, DevOps, and deployment concepts

---

##  Project Structure

.
├── docker-compose.yml
├── nginx
|   └── nginx.conf
│   └── Dockerfile
├── service_1
│   └── Dockerfile
|   └── app.go
├── service_2
│   └── Dockerfile
|   └── app.py
└── README.md