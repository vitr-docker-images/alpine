# Alpine Docker Image Copy

[![GHCR-Badges](https://ghcr-badge.egpl.dev/vitr-docker-images/alpine/tags?color=%2344cc11&amp;ignore=latest&amp;n=3&amp;label=image+tags&amp;trim=)](https://ghcr-badge.egpl.dev/)

This repository contains a copy of the Alpine Docker image. The image is stored on GitHub Container Registry (GHCR) and can be pulled using Docker CLI or used in a Docker Compose file.

## Why a Copy?

This copy is maintained to pin a particular version of the Alpine Docker image. Pinning allows for a more stable and predictable environment by eliminating the risks associated with unexpected updates or changes in the official image.

## Usage

### Pull the Image

To pull the image from GHCR, run:

```bash
docker pull ghcr.io/vitr-docker-images/alpine:3.9.0
```
