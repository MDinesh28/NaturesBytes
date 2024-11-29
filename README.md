### To remove image

    docker rmi -f $(docker images -qa)

### To kill container

    docker kill $(docker ps -qa)

### To remove container

    docker rm $(docker ps -qa)
