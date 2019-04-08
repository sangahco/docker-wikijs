[![HitCount](http://hits.dwyl.io/sangahco/sangahco/docker-wikijs.svg)](http://hits.dwyl.io/sangahco/sangahco/docker-wikijs)

# Server and Client for monitoring Docker containers

Docker images ready to run for Sensu server and client service.
The client has already a couple of plugins installed for monitoring docker containers, disk space and other few things.

## Requirements

First make sure *Docker* and *Docker Compose* are installed on the machine with:

    $ docker -v
    $ docker-compose -v

If they are missing, follow the instructions on the official website (they are not hard really...):

- [Docker CE Install How-to](https://docs.docker.com/engine/installation/)
- [Docker Compose Install How-to](https://docs.docker.com/compose/install/)


## How to Use

**Use the script `docker-auto.sh` to manage these services!**

    $ ./docker-auto.sh --help


## Settings Up the Environment

The following settings are available:


| Variable                | Description                                               | Default                |
|-------------------------|-----------------------------------------------------------|------------------------|
| WIKIJS_CONFIG_FILE      | The wikijs config file (create a config.yml)              | /opt/wikijs/config.yml |
| WIKIJS_GIT_FOLDER       | The wiki git folder for synchronization (should be empty) | /opt/wikijs/repo       |
| WIKIJS_ADMIN_EMAIL      | The admin email                                           |                        |
| GITLAB_PRIVATE_KEY_FILE | Private key to login into the git repository              |                        |
| HUB_INSTANCE            | If the hub is used give a name to this container          | wikijs                 |