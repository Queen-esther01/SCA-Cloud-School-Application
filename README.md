### Installation Guide

1. Install Docker on any VM of your choice in a cloud environment.
2. Clone this Github repository.
3. Cd into the root of this project and run the command `docker build -t sca-app:v1 .` If this command fails you can try again by appending `sudo` to the top of the command.
4. Run a container from the generated image by running `docker container run --publish 80:80 --detach --name sca-cloud-app sca-app:v1`
5. Then you can access your containerized application by **mapping your vm ipaddress to the expose port(80)**.

Goodluck.