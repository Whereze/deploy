#  Create and start containers. [-d] Run containers in the background, print new container names.
    docker-compose up -d

#  View output from containers. [--tail="all"] Number of lines to show from the end of the logs for each. container.
    docker-compose logs --tail 10

#  Stop services
    docker-compose stop

# Stops containers and removes containers, networks, volumes, and images created by up. [-t, --timeout TIMEOUT]   Specify a shutdown timeout in seconds (default: 10).
    docker-compose down -t1