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
![pull _images](https://github.com/juned171/dockerproject/blob/master/Screenshot%20(41).png)

## Docker-Compose:
Before using Docker-Compose you should install the software. For reference go to this website :[docker-compose]( https://docs.docker.com/compose/install/)  .

You can create and edit this file using vim editor. For that use vim docker-compose.yml. Remember the file name should always be docker-compose.yml.

![docker-compose](https://github.com/juned171/dockerproject/blob/master/Screenshot%20(42).png)

## Docker-compose up:
As per the below  picture use ```docker-compose ```   up to complete the setup.
![docker-compose](https://github.com/juned171/dockerproject/blob/master/Screenshot%20(43).png)

-after that the below processing takes place:
![docker-compose](https://github.com/juned171/dockerproject/blob/master/Screenshot%20(44).png)

## NEXTCLOUD STARTED :
Got to your browser and type localhost:8081  or by giving your IP address:8081  and done you will be able to see your Nextcloud WebApp. Try it in linux and windows both.
![windows](https://github.com/juned171/dockerproject/blob/master/Screenshot%20(39).png)
# IN LINUX  

![linux](https://github.com/juned171/dockerproject/blob/master/Screenshot%20(40).png)

I learned all this technology under Vimal Daga Sir under his campaigh IIEC_RISE for free!!
thankyou Vimal Sir!.
