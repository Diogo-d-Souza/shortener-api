# URL Shortener

## 📌 Project Overview
This project is a **URL Shortener API** built using **Spring Boot** and **MongoDB**. It allows users to shorten long URLs and be redirected to the original URL using the generated short id.

## 🛠️ Tech Stack
- **Java 21**
- **Spring Boot**
- **MongoDB**
- **Docker & Docker Compose**

---

##  🔨 How to Build and Run

### Clone the Repository**
```sh
git clone https://github.com/Diogo-d-Souza/shortener-api.git
cd shortener-api
```

### Build and Run the Docker Container**
```sh
docker docker compose up -d
```
## Stop and Remove the Containers and Volumes
```sh
docker compose down -v
```
---

## 📡 API Endpoints
| Method | Endpoint        | Description |
|--------|-----------------|-------------|
| `POST` | `/shorten`  | Shortens a URL |
| `GET` | `/{shorten-id}` | Redirects to the original URL |


---

This **URL Shortener** was a simple project to practice **Spring Boot, MongoDB, and Docker**.
Feel free to leave a feedback or modify it as needed!
