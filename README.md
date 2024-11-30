# keycloak-mariadb-nginx
Introduction
This project is a for running a secure Keycloak server in production with MariaDB as database and Nginx as reverse proxy with SSL enabled and certbot auto renewal.

**Prerequisites**

1. Docker Engine
2. Docker Compose
3. A valid domain name

**Installation**

1. Configure UFW to open required ports
2. Install NGINX for reverse proxy 
3. Configure NGINX for keycloak
4. use docker-compose.yml file and revise the parameter as required 
5. Run docker compose up -d to start the stack
