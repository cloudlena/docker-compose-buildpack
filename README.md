# Cloud Foundry Docker Compose Buildpack

> This is an **experiemnt** and therefore not to be used in production.

This buildpack installs the [Docker Engine](https://www.docker.com/products/docker-engine) and [Docker Compose](https://docs.docker.com/compose/) and allows to run Docker applications within the Cloud Foundry [Garden Container](https://docs.cloudfoundry.org/concepts/architecture/garden.html). This allows you to `cf push` ordinary `docker-compose.yml` files and have them run within Cloud Foundry.
