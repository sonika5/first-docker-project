# First Docker Project

A beginner Docker project demonstrating how to containerize a simple Python application.

## What I learned

* Created a Dockerfile
* Built a Docker image
* Ran a Docker container
* Viewed Docker images
* Tagged a Docker image
* Pushed the image to Docker Hub

## Docker Commands

```bash
docker build -t my-first-docker-image:latest .

docker images

docker run my-first-docker-image:latest

docker tag my-first-docker-image:latest YOUR_USERNAME/my-first-docker-image:latest

docker push YOUR_USERNAME/my-first-docker-image:latest
```

## Technologies

* Python
* Docker
* Docker Hub
