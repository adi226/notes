# Docker Commands

- List all containers: `docker ps -a`
- Retrieve container logs" `docker logs <container_id>`
- Get detailed container information: `docker inspect <container_id>`
- Stop docker container: `docker stop <container_id>`
- Delete container: `docker rm <container_id>`
- Remove all containers: `docker container prune -f`
- Disconnect container to run in background using `-d` or `--detach`
- Use `--since`, `--from`, `--until` or `--tail` with `docker logs <--flag> <container_id>`
- Use `-p` switch with incoming port to open in host and port mapped inside container with `docker run -p <host_machine_port>:<mapped_docker_port> <docker_image>`
- Use `-v` switch to map directory inside the container to a persistent storage: `docker run -v /your/dir:/docker/dir <docker image>`
- List docker images: `docker image ls`
- Image published to registry: `<repository_name>/<name>:<tag>`
- Download a image manually: `docker pull <repository_name>/<name>:<tag>`
- Download image and run container from docker hub or DNS: `docker run <repository_name>/<name>:<tag>`
