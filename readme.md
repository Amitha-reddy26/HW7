# Dockerization Project Summary

This document summarizes the key steps, experiences, and challenges faced during the Dockerization process.

## Key Steps
1. Created a Docker Hub account 
2. Created a new repository on Docker Hub 
3. Built the Docker image locally 
4. Tagged the local image with the Docker Hub repository name.  
5. Pushed the Docker image to the Docker Hub repository.  
6. Verified the image availability and tested pulling it on a different machine.  

## Challenges and Learnings
- Encountered version mismatches between local Docker and the base image, which required updating Docker Desktop.  
- Faced authentication errors during the first push to Docker Hub, resolved by reconfiguring Docker login credentials.  
- Learned the importance of using `.dockerignore` to reduce image size and speed up build times.  
- Gained insights into multi-stage builds to optimize image size and improve security.  
- Understood how to handle environment variables and secrets securely within Docker containers.  

