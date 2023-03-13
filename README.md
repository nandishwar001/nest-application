# PSCollab Microservices

This repo is a collection of Node.js microservices. The services are created in a framework called Nest, so everything in the [Nest.js docs](https://docs.nestjs.com/) applies here.

There are two ways to get started:

1. Docker (recommended)
2. Manual

> **Note:** All commands below assume the present working directory in your terminal to be the root of this repo folder.

## Getting Started with Docker

This is the simplest option where a developer only needs Docker installed on their local system. All system libraries and other dependencies to get the code up and running are automatically managed via Docker Compose.

In this setup, each microservice runs in its own Docker container. Common services, suchyes, as the message broker (eg. Redis), run in their own containers.

### Pre-requisites:

- [Docker Desktop](https://www.docker.com/products/docker-desktop) - It's the complete package with Docker engine, compose and other tooling available for Windows and Mac.

Steps to install the base folder dependencies - Required for local development

STEP 1: Open terminal for base folder

STEP 2: Run yarn install

### Run

Start the containers. This command will take a few minutes in its first run as it will need to download the required Docker images. Subsequent runs will be significantly faster.

```bash
$ docker-compose up
```
