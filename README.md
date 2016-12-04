# Cloud Foundry Docker Buildpack

> This is a container experiemnt and not to be used in production

This buildpack installs [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) and allows to run Docker containers within the Cloud Foundry [Warden Container](https://docs.cloudfoundry.org/concepts/architecture/warden.html). This allows you to `cf push` ordinary `Dockerfile`s or `docker-compose.yml` files.
