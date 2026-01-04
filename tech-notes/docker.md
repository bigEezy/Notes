# Docker

Overview: Containerization basics and common Docker commands.

Key commands:
- Build: `docker build -t myimage .`
- Run: `docker run -d --name myc myimage`
- List: `docker ps`, `docker images`
- Stop: `docker stop <container>`
- Remove: `docker rm <container>`, `docker rmi <image>`

Examples:
- Run with port: `docker run -p 8080:80 myimage`

Resources:
- https://docs.docker.com/
