# Containerization - Docker

Docker is used as the containerization tool, ensuring that all software instances across development, staging and production, run in a consistent enviroment.

The containerization also facilitates test automations and CI/CD workflows, Scalability and orchestration by Kubernetes and isolation between microservices, preventing dependency or conflicts.

## Structure
```
container/
|-- DockerFile
|-- docker-compose.yml
|-- .dockerignore
|-- container.md

```

## DockerFile
 - Using node:20-alpine for its small footprint and fast startup, which reduces build and deploy times.
 - Only essensial files are copied before installing dependencies.
 - Application is built during conternerization.

[View the Dockerfile](./Dockerfile)


## docker-compose.yml
 ** Use for local development only**
 - Builds the API service image locally
 - Sets environment variables via .env or inline
 - Can link optional services (like MongoDB) only in dev

[View the docker-compose.yml](./docker-compose.yml)