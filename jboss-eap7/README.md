JBoss EAP 7.0 Docker File
=========================

Based on Arun Gupta's example - `https://github.com/arun-gupta/docker-images`


Before building
---------------

Download the latest JBoss EAP 7.0 image from `http://www.jboss.org/products/eap/download/` into your working directory.


Build the Image
---------------

`docker build -t kraluk/jboss-eap:7.0-beta .`


Run the Image
-------------

`docker run -it kraluk/jboss-eap:7.0-beta`


Default User
------------
Name: `admin`
Password: `admin.678`
