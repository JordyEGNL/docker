# Docker Compose files for my home servers
[![Deployment](https://github.com/JordyEGNL/docker/actions/workflows/deployment.yml/badge.svg)](https://github.com/JordyEGNL/docker/actions/workflows/deployment.yml) [![Cleanup](https://github.com/JordyEGNL/docker/actions/workflows/cleanup.yml/badge.svg)](https://github.com/JordyEGNL/docker/actions/workflows/cleanup.yml)

This repository contains the Docker Compose files for my home servers. The Docker Compose files are automatically deployed to the servers using GitHub Actions. Most updates will be done automatically by Renovate, but some services require manual intervention.

## File structure
```
<HOST>
├── <SERVICE>
│   ├── docker-compose.yml
```