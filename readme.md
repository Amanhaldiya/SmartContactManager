# Smart Contact Manager 🧠📇

A full-stack contact management system built using **Microservices Architecture**, **Spring Boot**, **Docker**, and **OAuth2 Authentication**. Designed to be modular, secure, and scalable for enterprise-grade deployments.

## 🛠 Tech Stack

- **Backend**: Java, Spring Boot, Spring Security, Spring Cloud
- **Authentication**: OAuth2, JWT
- **Database**: MongoDB / MySQL (depending on service)
- **Containerization**: Docker, Docker Compose
- **Architecture**: Microservices (User Service, Contact Service, Auth Service)
- **Frontend**: React / Next.js (Optional UI integration)

## 📦 Microservices Overview

| Service         | Description                                        | Port |
|----------------|----------------------------------------------------|------|
| Auth Service    | Handles OAuth2 login & JWT token management        | 8081 |
| User Service    | Manages user profiles and roles                    | 8082 |
| Contact Service | Manages contact CRUD operations                    | 8083 |

## 🔐 Authentication Flow

- OAuth2 login via Google or GitHub
- JWT token issued to client
- Secure APIs using bearer tokens and role-based access

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/smart-contact-manager
cd smart-contact-manager
