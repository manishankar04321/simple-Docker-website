# Docker Static Website

This is a simple project to deploy a static website using Docker and Nginx.

##  Project Files

* Dockerfile
* index.html

##  How to Run

### 1. Build Docker Image

```
docker build -t my-website .
```

### 2. Run Container

```
docker run -d -p 8081:80 my-website
```

### 3. Open in Browser

```
http://localhost:8081
```

##  Concepts Used

* Dockerfile
* Docker Image
* Docker Container
* Port Mapping
* Nginx Web Server

##  Output

Displays a simple HTML page:
"Hello from Docker "


✅ This project is useful for beginners to understand Docker basics.
