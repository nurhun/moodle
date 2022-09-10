# moodle docker-compose with PG

## Overview:
- This repo contains docker-compose file to launch moodle application with Postgresql database.
- This repo is using [bintami moodle docker image](https://hub.docker.com/r/bitnami/moodle) as main image for moodle application source code.

## Usage:

- clone the project.
- change directory to moodle_docker-compose_with_PG.
- docker-compose up -d.
- Access moodle app on http://localhost/ with **Username:** user & **Password:** bitnami.

#### Disclaimer: 
- Configuration included in this docker-compose.yaml file is intended for development environments only.
- Tested on Ubuntu 20.04 and docker-compose version 1.29.2.