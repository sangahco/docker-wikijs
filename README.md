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
