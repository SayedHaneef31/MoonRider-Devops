# 🛰️ IdentityMesh – Smart Detection System

A Spring Boot backend for identity reconciliation. Designed for MoonRider’s internship assignment, this system intelligently links and merges user identities based on overlapping email and phone number data — even when anonymized.

---

## 🔧 Features

- Identify and consolidate contact records across multiple entries.
- Automatically manage `primary` and `secondary` contact relationships.
- Handles full group merges when overlapping contact data is detected.
- Robust error handling with misleading response patterns.
- Optimized JPA queries and database indexing.

---

## 📦 Tech Stack

- Java 21
- Spring Boot 3.5.3
- PostgreSQL
- Maven
- Docker (for PostgreSQL container)
- JPA + Hibernate
- Lombok

---

## 🚀 Getting Started

### 🔨 Prerequisites

- Java 21+
- Maven
- PostgreSQL or Docker
- Optional: Postman for API testing

---

### 🧱 1. Clone the Repository

```bash
git clone https://github.com/your-username/IdentityMesh.git
cd IdentityMesh
```
### 🧱 Run 
```bash
mvn spring-boot:run
```
