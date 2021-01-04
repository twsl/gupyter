# gupyter

![Build](https://github.com/twsl/gupyter/workflows/build/badge.svg)

Docker images for jupyter with GPU support

Inspired by [gpu-jupyter](https://github.com/iot-salzburg/gpu-jupyter), simplified by directly replacing the root/base image.
Takes the official jupyter dockerfiles from the [docker-stacks](https://github.com/jupyter/docker-stacks) repository and builds the following images:

- [base-notebook](https://github.com/users/twsl/packages/container/package/gupyter/base-notebook)
- [minimal-notebook](https://github.com/users/twsl/packages/container/package/gupyter/minimal-notebook)
- [scipy-notebook](https://github.com/users/twsl/packages/container/package/gupyter/scipy-notebook)
