# docker_setup

1. Make sure you have docker installed.
2. Run the commnad "docker build -t {your_name}/node-example:1 ." to build an image
3. Run the command "docker run -p {Your_port}/3001 {your_name}/node-example:1" to run the docker
4. To stop the docker, run the command "docker container ls" to check the container ID and then run "docker container stop {container_ID} "
