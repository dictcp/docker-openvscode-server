# docker-openvscode-server

It is an (alternative) arm64 and amd64 build of [openvscode-server](https://github.com/gitpod-io/openvscode-server).

The arm64 build allows openvscode-server running on ARM64 platforms, including Raspberry Pi, AWS Graviton2 and Ampere.


## Getting started

- Start the server:
```bash
docker run -it --init -p 3000:3000 -v "$(pwd):/home/workspace:cached" dictcp/openvscode-server
# Docker image is also available at ghcr.io/dictcp/openvscode-server
```
- Visit localhost:3000.

