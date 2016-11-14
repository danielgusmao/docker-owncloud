# ownCloud on Alpine 3.2

[![docker hub](https://img.shields.io/badge/docker-image-blue.svg?style=flat-round)](https://registry.hub.docker.com/u/splattael/owncloud/)
[![microbadger](https://images.microbadger.com/badges/image/splattael/owncloud.svg)](https://microbadger.com/images/splattael/owncloud)

## Docker run

    docker run \
      --link mysql:mysql
      --name owncloud \
      -P \
      splattael/owncloud

## Software

* apache2-2.4.16-r1
* php-apache2-5.6.27-r0
* owncloud 9.1.2 (from source)

## Notes

### 8.1.3

* Don't forget to copy `ca-bundle.crt` into your `VOLUME`/config directory
