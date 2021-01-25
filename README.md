# wp-docker

containerize wordpress application  
rely on:
* https://hub.docker.com/_/wordpress/
* https://hub.docker.com/_/mysql/

## .env

```
WP_DB_HOST=host.docker.internal # depend on your server
WP_DB_NAME=dbname
WP_DB_USERNAME=dbuser
WP_DB_PASSWORD=dbpassword

DOCKER_WORDPRESS_PORT=8888 # your host port for wordpress app
```

## directory structure
* `./app` : where your wp app source code are stored
