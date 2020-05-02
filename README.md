# NEXTCLOUD_IIEC_RISE_DOCKER_COMPOSE PROJECT
Nextcloud is a  safe home for all your data. Access &amp; share your files, calendars, contacts, mail &amp; more from any device, on your terms.

This project is built with
-RedHat Linux RHEL8
-Docker
-nextcloud
-Mariadb


## Setting up the required things:

Firewall might create some networking issues so stop the firewall.
```systemctl start firewalld```
Starting the docker:

``` systemctl start docker ```to start Docker Service.
## Downloading required images:
Pulling Mariadb Image:
Use 
```docker pull mariadb:latest ``` 
to download the mariadb  image to use as a database server.

-To know more about Mariadb Image go to this page:[mariadb](https://hub.docker.com/_/mariadb)

-Now to pull nextcloud image:
```docker pull nextcloud``` 

to download the Nextcloud image in which apache server is already preconfigured.
To know more about Nextcloud image  go to this page: [NEXTCLOUD](https://hub.docker.com/_/nextcloud)
