# Docker Command Checklist

A practical checklist to learn and master Docker, from basic commands and container management to networking, volumes, Docker Compose, registries, and advanced workflows.

## 01. Check Docker and Get Started

* [ ] `docker --version` — Display the Docker CLI version
* [ ] `docker version` — Display client and server versions
* [ ] `docker info` — Show Docker system information
* [ ] `docker help` — Display Docker command help
* [ ] `docker login` — Authenticate with a container registry
* [ ] `docker logout` — Sign out of a container registry

## 02. Images

* [ ] `docker images` — List local images
* [ ] `docker pull nginx` — Download an image from a registry
* [ ] `docker build -t myapp .` — Build an image from a Dockerfile
* [ ] `docker tag myapp myapp:v1` — Add a tag to an image
* [ ] `docker image inspect nginx` — Display image metadata
* [ ] `docker image rm nginx` — Remove a local image
* [ ] `docker image prune` — Remove unused images

## 03. Containers

* [ ] `docker run nginx` — Create and run a container
* [ ] `docker run -d --name web nginx` — Run a named container in the background
* [ ] `docker ps` — List running containers
* [ ] `docker ps -a` — List all containers
* [ ] `docker stop web` — Stop a running container
* [ ] `docker start web` — Start an existing stopped container
* [ ] `docker restart web` — Restart a container
* [ ] `docker rm web` — Remove a stopped container
* [ ] `docker container inspect web` — Display container details

## 04. Logs and Debugging

* [ ] `docker logs web` — Display container logs
* [ ] `docker logs -f web` — Follow logs in real time
* [ ] `docker exec -it web sh` — Open an interactive shell in a running container
* [ ] `docker top web` — Display processes running inside a container
* [ ] `docker stats` — Monitor container resource usage
* [ ] `docker inspect web` — Display detailed Docker object information
* [ ] `docker cp web:/path/file.txt ./file.txt` — Copy a file from a container to the host

## 05. Ports and Networking

* [ ] `docker run -d -p 8080:80 --name web nginx` — Publish container port 80 on host port 8080
* [ ] `docker port web` — Display published port mappings
* [ ] `docker network ls` — List Docker networks
* [ ] `docker network create app-net` — Create a network
* [ ] `docker network inspect app-net` — Inspect network configuration
* [ ] `docker network connect app-net web` — Connect a container to a network
* [ ] `docker network rm app-net` — Remove a network

## 06. Volumes and Storage

* [ ] `docker volume ls` — List Docker volumes
* [ ] `docker volume create app-data` — Create a named volume
* [ ] `docker volume inspect app-data` — Inspect a volume
* [ ] `docker run -v app-data:/data nginx` — Mount a volume at `/data`
* [ ] `docker volume rm app-data` — Remove a volume
* [ ] `docker volume prune` — Remove unused volumes

## 07. Dockerfile and Building

* [ ] `docker build -t myapp .` — Build an image using the current directory
* [ ] `docker build -f Dockerfile.dev -t myapp:dev .` — Build using a specific Dockerfile
* [ ] `docker run --rm myapp` — Remove the container automatically after it exits
* [ ] `docker history myapp` — Display image build history
* [ ] `docker image inspect myapp` — Inspect image configuration and metadata

## 08. Docker Compose

* [ ] `docker compose version` — Display the Compose version
* [ ] `docker compose up` — Create and start services
* [ ] `docker compose up -d` — Start services in the background
* [ ] `docker compose down` — Stop and remove project containers and networks
* [ ] `docker compose ps` — List project containers
* [ ] `docker compose logs` — Display service logs
* [ ] `docker compose logs -f` — Follow service logs
* [ ] `docker compose exec app sh` — Open a shell in a running service container
* [ ] `docker compose build` — Build service images
* [ ] `docker compose pull` — Pull service images

## 09. Cleanup and Resources

* [ ] `docker system df` — Display Docker disk usage
* [ ] `docker container prune` — Remove stopped containers
* [ ] `docker image prune` — Remove dangling images by default
* [ ] `docker network prune` — Remove unused networks
* [ ] `docker system prune` — Remove unused Docker resources
* [ ] `docker system prune -a` — Remove unused resources, including unused images

## 10. Registries and Sharing

* [ ] `docker login` — Authenticate with a registry
* [ ] `docker tag myapp username/myapp:v1` — Tag an image for a registry account
* [ ] `docker push username/myapp:v1` — Upload an image to a registry
* [ ] `docker pull username/myapp:v1` — Download a published image
* [ ] `docker manifest inspect nginx` — Inspect an image manifest

## 11. Environment and Resource Limits

* [ ] `docker run -e APP_ENV=development myapp` — Set an environment variable
* [ ] `docker run --env-file .env myapp` — Load environment variables from a file
* [ ] `docker run --memory=512m myapp` — Limit container memory
* [ ] `docker run --cpus=1 myapp` — Limit container CPU usage
* [ ] `docker update --memory=1g web` — Update the memory limit of an existing container

## 12. Advanced Workflows

* [ ] `docker compose watch` — Watch files and synchronize or rebuild services when supported by the Compose configuration
* [ ] `docker context ls` — List Docker contexts
* [ ] `docker context use default` — Switch to the default Docker context
* [ ] `docker scout quickview myapp` — View an image's security overview with Docker Scout
* [ ] `docker buildx build -t myapp .` — Build an image using Buildx
* [ ] `docker save -o myapp.tar myapp` — Export an image to a tar archive
* [ ] `docker load -i myapp.tar` — Load images from a tar archive

---

## Progress Tracker

* **Total checklist items:** 71
* **Completed:** 0
* **Goal:** Learn each command and practice building, running, debugging, and deploying containers.

## Learning Resources

* [Official Docker Documentation](https://docs.docker.com/)
* [Docker Get Started Guide](https://docs.docker.com/get-started/)
* [Docker CLI Reference](https://docs.docker.com/reference/cli/docker/)
* [Docker Compose Documentation](https://docs.docker.com/compose/)
* [Dockerfile Reference](https://docs.docker.com/reference/dockerfile/)
* [Docker Buildx Documentation](https://docs.docker.com/build/buildx/)
* [Docker Scout Documentation](https://docs.docker.com/scout/)

---

## Practice Tips

* Start with a small image such as `nginx` or `hello-world`.
* Learn the difference between images, containers, volumes, and networks.
* Use `docker ps -a` to find stopped containers.
* Use `docker logs` and `docker inspect` to investigate problems.
* Be careful with `docker rm`, `docker volume prune`, and `docker system prune -a`; cleanup operations can remove data or resources you still need.
* Replace example names such as `myapp`, `web`, and `username` with your own values.
* Some commands require a running Docker daemon, registry authentication, a compatible Docker Compose version, or additional tools.

⭐ **Keep building, keep testing, and master Docker one command at a time!**
