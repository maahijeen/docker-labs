# 🐳 Docker Labs

This repo contains my **Docker practice files and notes**.  
I use it to learn containerization and experiment with simple projects.  

---

## 📦 Topics Covered
- Building Docker images  
- Running containers  
- Docker Compose basics  
- Hosting sample apps (Node.js / WordPress / Nginx)  

---

## ⚡ Example Command
```bash
# Build Docker Image
docker build -t myapp .

# Run Container
docker run -p 8080:80 myapp
