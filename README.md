# container-portainer

A Docker compose container setup for [Portainer](https://www.portainer.io/).

## Table of contents

- [container-portainer](#container-portainer)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)

## Setup

0. Requirements

   - Docker
   - Docker Compose
   - A running [Traefik instance](https://github.com/jonas-merkle/container-traefik)

1. Add environment variables

    Add the missing information for the environment variables:

    ```bash
    nano .env
    ```

2. Start container

    ```bash
    docker-compose up -d
    ````

3. Stop container

    ```bash
    docker-compose down
    ```
