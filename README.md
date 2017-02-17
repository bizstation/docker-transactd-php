docker-transactd-php
================================================================================

This is the Git repository of the Docker image for Transactd PHP client.

* [Docker Hub page](https://hub.docker.com/r/bizstation/transactd-php/)
* [Transactd](https://github.com/bizstation/transactd/)


## Supported Versions

This image contains the official image [php](https://hub.docker.com/_/php/).
Modify Dockerfile to use another version of PHP.

* `FROM php:XXX` : Set Docker image version. (ex. `latest`, `7.0`, `5` ...)
* `ENV PHP_VERSION X.X` : Set PHP version in `MAJOR.MINOR` format.

### Transactd 3.7.2 (2017.02.17)

* PHP 7.1
* PHP 7.0
* PHP 5.6
