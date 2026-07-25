# Docker Learning:

# 1. What is Docker?
- Docker is a platform designed to help developers build, share and run container applications.

# 2. Why we need Docker?
## Problem 1:
- Applications often behave differently in development, testing and production env due to variations in configuration, dependencies and infrastructure.

## Solution 1:
- Docker containers encapsulate all the necessary components, ensuring the application runs consistently across all env. 

# Docker Working and Components:
## 1. Docker Engine (Docker Daemon):
- Responsible for creating, running and managing docker containers.
- Serves as the runtime that powers Docker's Containerization Capabilities.
- Background service running on the host.
- Manages Docker objects such as images, containers, networks and volumes.
- Interaction: Through REST APIs, operations(start, stop, restart etc.)

## 2. Docker CLI:
- Tool that users interact with to communicate with the Docker Daemon.
- Commands like building images, running containers and managing Docker resources.

## 3. REST APIs:
- Helps to communicate btw Docker Engine and CLI.
- Devs use to automate Docker operations or integrate Docker functionality to their apps.