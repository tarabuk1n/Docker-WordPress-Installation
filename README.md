# Docker WordPress Installation

![Docker Wordpress](https://www.davidguida.net/assets/uploads/2017/06/dockerPress.png)

Automating WordPress Installation Through Docker:

- Configuring MySQL container
- Configuring Nginx container (reverse-proxy realization)
- Configuring WordPress container (last build) 
- Creating a local database backup 
- Backing up content (volumes)

There are 2 implementations: **root user** (_everything in docker-compose file_), or **non-root users** (_nginx container is compiling from Dockerfile_). The hostname is specified in the _default.conf_ file.
