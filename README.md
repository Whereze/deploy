#  Create and start containers. [-d] Run containers in the background, print new container names.
    docker-compose up -d

#  View output from containers. [--tail="all"] Number of lines to show from the end of the logs for each. container.
    docker-compose logs --tail 10

#  Stop services
    docker-compose stop
