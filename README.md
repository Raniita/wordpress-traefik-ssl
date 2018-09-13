# Wordpress + Traefik + SSL (Docker way)
I recently create a easy solution for set up a wordpress page with 1 
command. 
I guess that it would be good to share.

## Getting Started
These instructions will get you to the set up of the enviroment for the 
webpage. 

For the project i use docker as container, traefik as proxy reverse(and SSL 
managing), mariadb for database, phpmyadmin for database managing and ,of 
course, wordpress.

### Prerequisites
You need to install this software

```
docker docker-compose
```

### Installing 
Frist of all, clone the project

```
git clone https://github.com/Raniita/wordpress-traefik-ssl.git
```

Go inside the folder and configure your enviroment. You must edit the .env 
file and the traefik.toml (only insert the email).
After, execute 
```
docker-compose up
```
that command will execute all the containers and u will see all the logs 
about that, should check it to know if we have a problem with the webpage.


##Tested
Currently, i have tried on my homelab with Fedora Server 28 and a server 
with 
Ubuntu Server 18.04.1 LTS and everything works fine.
