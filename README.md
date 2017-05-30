# nifi
Repository for nifi templates


# Run nifi in Docker

docker run -d -it --privileged -v /demos/nifi/tweetsBrex:/tweets --name nifi -p 8080-8081:8080-8081 mkobit/nifi

docker exec -it nifi bash

# Import templates 

Import the xml in democenter:8080/nifi
