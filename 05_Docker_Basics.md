---

# 🐳 5. Docker Basics

## 🔹 What is Docker?
Docker is a **containerization tool** that packages apps with all dependencies.

---

## 🔹 Core Concepts
| Term | Meaning |
|------|----------|
| Image | Template for containers |
| Container | Running instance of an image |
| Dockerfile | Blueprint to build images |
| Docker Hub | Repository for images |

---

## 🔹 Common Commands
| Command | Description |
|----------|--------------|
| `docker pull nginx` | Download image |
| `docker run -d -p 8080:80 nginx` | Run container |
| `docker ps` | Show running containers |
| `docker stop <id>` | Stop container |
| `docker build -t myapp:v1 .` | Build image |
| `docker push user/myapp:v1` | Upload image |

---

## 🔹 Sample Dockerfile
```dockerfile
FROM node:18
WORKDIR /app
COPY . .
RUN npm install
CMD ["npm", "start"]
