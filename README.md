# gupyter

![Build](https://github.com/twsl/gupyter/workflows/Docker/badge.svg)

Docker images for jupyter with GPU support

Inspired by [gpu-jupyter](https://github.com/iot-salzburg/gpu-jupyter), simplified by directly replacing the root/base image.
Takes the official jupyter dockerfiles from the [docker-stacks](https://github.com/jupyter/docker-stacks) repository and builds the following images:

- [base-notebook](https://github.com/users/twsl/packages/container/package/gupyter/base-notebook)
- [minimal-notebook](https://github.com/users/twsl/packages/container/package/gupyter/minimal-notebook)
- [scipy-notebook](https://github.com/users/twsl/packages/container/package/gupyter/scipy-notebook)

GPU support is added via [nvidia/cuda](https://hub.docker.com/r/nvidia/cuda) images, defined by tags within the `strategy.json` file.
