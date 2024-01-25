# Docker composition of Nextcloud

Composition of containers for using Nextcloud

## How to use

### Clone repo and open its directory

```sh
git clone https://github.com/rudyson/nextcloud_docker-compose.git
cd nextcloud_docker-compose
```

### Copy dist env files and provide your parameters

```sh
cp -v mariadb.dist.env mariadb.env
cp -v phpmyadmin.dist.env phpmyadmin.env
```

### Start composition of containers

```sh
docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d
```

Go to [http://localhost](http://127.0.0.1:80) and install the system.

## Links

* [Fork source](https://github.com/EvilFreelancer/docker-nextcloud)
* [Nextcloud website](https://nextcloud.com/)
* [Nextcloud on Github](https://github.com/nextcloud)
* [Nextcloud on Docker Hub](https://hub.docker.com/_/nextcloud/)
