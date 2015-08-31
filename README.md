# Sweetstack

A modified PHPStack capable of running in OSX with docker-machine. You can find the original phpstack project at https://github.com/kasperisager/phpstack

A huge thanks to kasperisager for the inspiration and great work in putting this together.

## What's inside

* [Nginx](http://nginx.org/)
* [MySQL](http://www.mysql.com/)
* [PHP-FPM](http://php-fpm.org/)
* [HHVM](http://www.hhvm.com/)
* [Memcached](http://memcached.org/)
* [Redis](http://redis.io/)

### Requirements

* [Docker](https://docker.com/)
* [Docker Compose](http://docs.docker.com/compose/)
* [VirtualBox](https://www.virtualbox.org/) (optional)

### Instructions

```sh
# Clone the repository
$ git clone ctestama/sweetstack
$ cd sweetstack

# Boot up the Docker containers
$ docker-compose up
```

---
Licensed under the terms of the [MIT License](LICENSE.md).
