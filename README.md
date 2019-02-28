[![last-commit](https://img.shields.io/github/last-commit/Luismcplopes/docker-ubuntu.svg?logo=github)](https://img.shields.io/github/last-commit/Luismcplopes/docker-ubuntu.svg?logo=github)
[![docker build](https://img.shields.io/docker/build/luismcplopes/docker-ubuntu.svg?logo=docker)](https://img.shields.io/docker/build/luismcplopes/docker-ubuntu.svg?logo=docker)
![Docker Pulls](https://img.shields.io/docker/pulls/luismcplopes/docker-ubuntu.svg?logo=docker)
[![license](https://img.shields.io/github/license/Luismcplopes/docker-ubuntu.svg?logo=github)](https://img.shields.io/github/license/Luismcplopes/docker-ubuntu.svg?logo=github)
## Ubuntu Dockerfile

This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/_/ubuntu/) published to the public [Docker Hub Registry](https://hub.docker.com/r/luismcplopes/docker-ubuntu/).


### Base Docker Image

* [ubuntu:latest](https://hub.docker.com/r/library/ubuntu/)


### Installation

1. Install [Docker](https://docs.docker.com/install/).

2. Download [automated build](https://hub.docker.com/r/luismcplopes/docker-ubuntu/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull luismcplopes/docker-ubuntu`

   (alternatively, you can build an image from Dockerfile: `docker build -t="Luismcplopes/docker-ubuntu" github.com/Luismcplopes/docker-ubuntu`)

[![Try in PWD](https://cdn.rawgit.com/play-with-docker/stacks/cff22438/assets/images/button.png)](http://play-with-docker.com)

### Usage

    docker run -it --rm Luismcplopes/docker-ubuntu
