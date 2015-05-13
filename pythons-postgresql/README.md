dcreager/pythons-postgresql
===========================

Dockerfile for an Ubuntu 14.04 LTS container with serveral Pythons (as defined
by [rouge8/python](https://github.com/rouge8/Dockerfiles/pythons)), Docker, and
PostgreSQL 9.4 installed.

<https://index.docker.io/u/dcreager/pythons-postgresql/>

## Usage

    sudo docker pull dcreager/pythons-postgresql
    sudo docker run -i -t dcreager/pythons-postgresql /bin/bash  # many Python will be available in $PATH
