# Docker Container Directory

This folder is where the source docker files lives for the \"${DOCKER_APACHE_APP_NAME}\" container. 

Only use contents here when you need to update \"${DOCKER_APACHE_APP_NAME}\" docker image.

## To build
\`docker-compose build\`
\`docker tag ${DOCKER_HUB_IMAGE_URL} ${DOCKER_HUB_IMAGE_URL}:$tag\`
\`docker push ${DOCKER_HUB_IMAGE_URL}\`