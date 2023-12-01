# WordPress Docker Quick Start

### Quick Start Instructions

WordPress Docker Quick Start is a simple docker-compose setup to get started with docker with WordPress easily in olly a few steps.

> git clone git@github.com:aihimel/wp-docker-quick-start.git

> cd wp-docker-quick-start

> cp .env.sample .env 

> docker-compose up --build

YES! Your WordPress installation is up and ready to go.

### List of Containers

There are 3 services in the docker compose file.

+ WordPress Server
+ Mariadb Database
+ Adminer to access the database

### Default Folder Structures

In this composition folder structure is set up in a different and flexible way. To obtain the following features.

+ Plugins and Themes folders are easily accessible.
+ The entire composition is highly portable. You can just copy the entire folder and move to any other machine and everything will be good to go.
+ Configurability, this composition is highly configurable.

`database-volume`

This folder is to store all the data from databases. So when you want to port the project to anywhere else, the database will persist.

`plugins`

All your plugins will go in this folder.

`themes`

All the themes will go in this folder

`wordpress`

WordPress core files will be here

`xdebug`
xDebug configuration files.