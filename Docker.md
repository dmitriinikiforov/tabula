### Create container and run bash

    docker run --name <name> --rm -i -t <image> bash

### Execute bash shell on running container

    docker exec -it <container_name> bash