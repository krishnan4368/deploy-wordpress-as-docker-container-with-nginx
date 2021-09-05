# Dockerize-WordPress
This GitHub repository contain docker-compose file and instructions to deploy WordPress on docker container.

WordPress is the most popular content management system. It’s written in PHP, stores data in a MySQL database, and usually runs behind an Apache web server. These dependencies add several packages to your system and can be tricky to maintain over time. Here’s how to quickly launch a containerized WordPress install using the official Docker image.

Running WordPress in Docker requires two separate containers: a web container, running Apache and PHP, and a database container, hosting MySQL. You must also set up Docker volumes for the WordPress data directories. These store your configuration files and uploaded media so they persist across container restarts.

Create a new directory for your site, then clone this repo into it.

run command docker-compose up -d
