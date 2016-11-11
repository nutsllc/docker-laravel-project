# Docker Laravel Project

This is a develop environment for Laravel that is PHP framework on Docker.

## Require

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)

## Getting Start

```bash
git clone https://github.com/nutsllc/docker-laravel-project.git
cd docker-laravel-project
docker-compose up -d
```

``laravel`` directory appears on root directory of this repository after ``run docker-compose up``. 

All of the source of the Laravel are in it and it mount ``/var/www/laravel`` in the container.

## Using your own project

If you already have your own project, you can use it.

Before ``docker-compose up -d``, palce your project in directory the same as ``docker-compose.yml`` and it shuld be named ``laravel``.

Finally, run ``docker-compose up -d``.