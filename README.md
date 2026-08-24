# Docker Compose + Nginx Reverse Proxy

A hands-on DevOps project demonstrating how to run containerized services with Docker Compose, connect containers through a custom Docker network, and use Nginx as a reverse proxy for Mongo Express.

## Architecture

```text
Browser
   ↓
Nginx :8080
   ↓
Mongo Express :8081
   ↓
MongoDB :27017
