![Docker Wordpress](https://www.davidguida.net/assets/uploads/2017/06/dockerPress.png)
Automating WordPress Installation Through Docker:

- Configuring MySQL container
- Configuring Nginx container (reverse-proxy realization)
- Configuring WordPress container (last build) 
- Creating a local database backup 
- Backing up content (volumes)

There are 2 implementations: root user (everything in docker-compose file), or non-root users (nginx container is compiling from Dockerfile). The hostname is specified in the default.conf file.
