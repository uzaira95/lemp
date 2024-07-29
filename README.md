# Build a LEMP Server with Docker Compose

## Install Docker Compose on Ubuntu VM

1. Run the following command to download the docker compose binary.
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

2. Give it executable permissions
sudo chmod +x /usr/local/bin/docker-compose

3. Run the docker compose version command
docker-compose --version
