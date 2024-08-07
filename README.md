# Build a LEMP Server with Docker Compose

## What is LEMP?

We know that LEMP is an open-source web application stack which is used to develop web applications. It stands for Linux, NGINX, MySQL and PHP. In this repository, you'll find the Docker Compose YAML file which installs the following 4 services:

1. NGINX
2. MySQL
3. PHP
4. PHPmyAdmin

## Install Docker Compose on Ubuntu VM

1. Run the following command to download the docker compose binary.
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

2. Give it executable permissions
sudo chmod +x /usr/local/bin/docker-compose

3. Run the docker compose version command
docker-compose --version

## Important Note

Make sure to change the passwrod in the .env file and the index.php file in the src directory. The password in the .env file should be used everywhere to avoid any issues with the DB connectivity.
