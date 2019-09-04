# What is jsonnet?

> Jsonnet is a data templating language for application and tool developers, based on JSON.

[https://jsonnet.org](https://jsonnet.org)

# TL;DR;

```bash
$ docker run --name jsonnet bitnami/jsonnet:latest
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.
* All Bitnami images available in Docker Hub are signed with [Docker Content Trust (DTC)](https://docs.docker.com/engine/security/trust/content_trust/). You can use `DOCKER_CONTENT_TRUST=1` to verify the integrity of the images.
* Bitnami container images are released daily with the latest distribution packages available.

# Supported tags and respective `Dockerfile` links

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/containers/how-to/understand-rolling-tags-containers/).


* [`0.13-ol-7`, `0.13.0-ol-7-r80` (0.13/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-git/blob/0.13.0-ol-7-r80/0.13/ol-7/Dockerfile)
* [`0.13-debian-9`, `0.13.0-debian-9-r79`, `0.13`, `0.13.0`, `0.13.0-r79`, `latest` (0.13/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-git/blob/0.13.0-debian-9-r79/0.13/debian-9/Dockerfile)

Subscribe to project updates by watching the [bitnami/jsonnet GitHub repo](https://github.com/bitnami/bitnami-docker-jsonnet).

# Get this image

The recommended way to get the Bitnami Git Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/bitnami/jsonnet).

```bash
$ docker pull bitnami/jsonnet:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/bitnami/jsonnet/tags/) in the Docker Hub Registry.

```bash
$ docker pull bitnami/jsonnet:[TAG]
```

If you wish, you can also build the image yourself.

```bash
$ docker build -t bitnami/jsonnet:latest 'https://github.com/bitnami/bitnami-docker-jsonnet.git#master:0.13/debian-9'
```

# Configuration

## Running commands

To run commands inside this container you can use `docker run`, for example to evaluate jsonnet code:

```bash
$ docker run --name jsonnet bitnami/jsonnet:latest -e "{hello: 'world'}"
```

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-jsonnet/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-jsonnet/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-jsonnet/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License

Copyright 2019 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
