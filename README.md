# Flask Docker Setup

This guide provides step-by-step instructions to set up and run a Flask application using Docker.

## Prerequisites
- Install [Docker](https://www.docker.com/get-started) on your system.
- Ensure `docker` is running.

## Steps to Build & Run
---

- Clone the Repository
```bash
git clone <repository-url>
cd <project-folder>
```


- Build the Docker Image
```bash
docker build -t flask-app .
```

- Run the Flask Application in Docker
```bash
docker run -d -p 5000:5000 flask-app
```

Thanks