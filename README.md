# Dockerpress
Docker compose for dockerized WordPress + MySQL + Adminer. 

## Contains:
* MySQL 5.7
* WordPress 
  * PHP7.4
  * Apache
* Adminer - a light-weight alternative to phpMyAdmin 

This docker compose downloads ceghap/wordpress_memcached. This image is a normal WordPress docker image with php-memcached enabled. 

## Requirement
1. Docker installed & running. Download [Docker](https://www.docker.com/get-started).
1. Code editor. I recommend [VS CODE](https://code.visualstudio.com/).
1. [Git](https://git-scm.com/)

## Getting started
1. Clone this repo `git clone git@github.com:ceghap/dockerpress.git`
1. Go to the repo directory `cd dockerpress`
1. Edit `.env` file with your secure credentials.
1. Build the dockerpress container `docker-compose up -d --build`
1. Check browser:
    * WordPress: [http://localhost:8000](http://localhost:8000)
    * Adminer: [http://localhost:8080](http://localhost:8080) 
