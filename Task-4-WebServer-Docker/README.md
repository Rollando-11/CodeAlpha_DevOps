# Task 4 – Web Server using Docker

## Objective

Deploy a simple web server inside a Docker container using Nginx.

## Description

This project demonstrates the basics of Docker containerization by hosting a simple HTML webpage inside an Nginx container.

## Technologies Used

* Docker
* Nginx
* HTML

## Project Structure

```
Task-4-WebServer-Docker/
├── Dockerfile
├── index.html
├── README.md
└── screenshots/
```

## How to Build

```bash
docker build -t codealpha-webserver .
```

## How to Run

```bash
docker run -d -p 8080:80 --name webserver codealpha-webserver
```

## Output

After running the container, open your browser and visit:

```
http://localhost:8080
```

You should see the HTML page served by the Nginx web server running inside the Docker container.

## Learning Outcomes

* Understanding Docker images and containers.
* Creating a Dockerfile.
* Running a web server using Docker.
* Managing containers with basic Docker commands.
