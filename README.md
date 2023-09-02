# container-portainer

A Docker compose container setup for [Portainer](https://www.portainer.io/).

## Table of contents

- [container-portainer](#container-portainer)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)
    - [0. Requirements](#0-requirements)
    - [1. Add environment variables](#1-add-environment-variables)
  - [Usage](#usage)
    - [Start container](#start-container)
    - [Stop container](#stop-container)

## Setup

### 0. Requirements

- Docker
- (Docker Compose)
- A running [Traefik instance](https://github.com/jonas-merkle/container-traefik)

### 1. Add environment variables

Add the missing information for the environment variables:

```bash
nano .env
```

Mark the `.env` file so it's not tracked by git:

```bash
git update-index --assume-unchanged .env
```

## Usage

### Start container

```bash
docker compose up -d
````

### Stop container

```bash
docker compose down
```
