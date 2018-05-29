# WebApp - Linux Server

IP address: 35.180.95.0,
SSH port: 2200,
URL: http://35.180.95.0.xip.io,

## Prerequisites

* sqlalchemy
* PostgreSQL
* flask
* requests
* wsgi
* git

## Configuration Changes

* Added user grader - sudo rights
* Created a postgresql user and database with limited permissions.
* Changed ssh port to port 2200
* Configured Firewal(UFW) to strictly allow connections from ports 2200, 80 and 123
* Enabled secure ssh key pair login, thus disabling remote connections
* Disabled directory listing
* Adjusted the application to running as WSGI app

## External Resources

* http://digitalocean.com
* https://stackoverflow.com
* https://github.com/skh/fsnd-linux-server-config
