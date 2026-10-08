# Dockerfile Basics

## Question

Why are Dockerfile Basics important in software engineering?

## Short Answer

A Dockerfile is a text configuration script containing a sequential set of instructions used by Docker to automate image construction. Common instructions include `FROM` to specify the parent image, `COPY` to transfer project files from the host, `RUN` to execute package installation commands, and `CMD` to declare the default container process. Each instruction creates a cached layer, optimizing subsequent build times.

## Simple Example

```dockerfile
FROM python:3.11-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python", "server.py"]
```

## Key Point

A Dockerfile script defines the reproducible recipe of layers that assemble a container image.

<!-- date: 2026-10-08 -->
