# Item Catalog - Udacity
### Full Stack Web Development ND
_______________________
## About

In this project we use AWS Lightsail to configure a Ubuntu linux server to be used as a secure webserver.

##IP/URL
52.37.16.101

## Summary of Software Installed
* Python 3
* Python libraries
  + flask, sqlalchemy, oauth2client, requests
* mod_wsgi for python3
* postgresql

## Summary of Configurations made
* Disabled remote ssh login as root
* Created a new account "grader" which has sudo access. Password for "grader" is "grader" without the double quotes.
* ssh port was changed to 2200
* Key based ssh authentication is enforced
* UFW is configured to allow incoming traffic only from ports 2200, 80, 123
* Web server has been configured to serve the Item Catalog application as a WSGI app on port 80

## Third Party Resources used
+ https://www.codementor.io/abhishake/minimal-apache-configuration-for-deploying-a-flask-app-ubuntu-18-04-phu50a7ft
+ https://askubuntu.com/questions/27559/how-do-i-disable-remote-ssh-login-as-root-from-a-server

## Authors
* Ambuj Agrawal




