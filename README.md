# Simple Node.js App for Docker

This is a minimal Node.js application created for learning Docker.

## What it does

- Runs a simple HTTP server
- Exposes a port
- Used to practice Dockerfile, build, and run on AWS EC2

## How to run (Docker)

```bash
docker build -t lesson1-node .
docker run -p 80:3000 lesson1-node
```
