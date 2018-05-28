# WebApp - Linux Server

IP address: 35.180.95.0
SSH port: 2222
URL: http://35.180.95.0.xip.io

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
* Changed ssh port to port 2222
* Configured Firewal to strictly allow connections from ports 2222, 80 and 123
* Enabled secure ssh key pair login

## External Resources

* http://digitalocean.com
* https://stackoverflow.com
