# docker-pocketbase

[![ci](https://github.com/quangthe/docker-pocketbase/actions/workflows/build-docker.yaml/badge.svg)](https://github.com/quangthe/docker-pocketbase/actions/workflows/build-docker.yaml)
[![Docker Stars](https://img.shields.io/docker/stars/pcloud/pocketbase.svg?style=flat)](https://hub.docker.com/r/pcloud/pocketbase/)
[![Docker Pulls](https://img.shields.io/docker/pulls/pcloud/pocketbase.svg?style=flat)](https://hub.docker.com/r/pcloud/pocketbase/)

[pocketbase](https://pocketbase.io/) Alpine-based Docker image

Build docker image
```shell
docker build -t pcloud/pocketbase .
```

Run container
```shell
docker run --name pocketbase -p 8080:8080 -v /path/to/data:/pb/pb_data pcloud/pocketbase
```
