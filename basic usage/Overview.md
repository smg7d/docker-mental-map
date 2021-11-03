[Docker](https://www.docker.com/) is an [open-source project](https://github.com/docker/docker) for automating the deployment of applications as portable, self-sufficient containers that can run on the cloud or on-premises.

Docker encapsulates applications within their own filesystems so that applications can be run across different operating systems and physical machines.

A dockerfile defines a filesystem, that is the application code, the libraries used to run that code, additional resources, environment variables, and system settings, all within its own directory. 

dockerfiles are built into docker images, which when run become docker containers. a docker container is a running instance of the docker image defined by the docker file.

basic usage of docker involves defining a dockerfile, building that dockerfile into a docker image, placing that image into a place where the physical machine that will run the image can access it, and then running that image as its own container.

docker images are stored in accessible repositories, such as docker hub.

docker containers have their own memory space that is created and deleted when the container is run and shut down respectively. therefore, persisting data outside that container takes some work.

volumes are uses to persist storage outside of the docker container - a volume is a defined space on a physical machine's directory which can be "mounted" to other "machines" including docker containers. 

they come in two flavors - named volumes and bind mounts. 

docker containers can only talk to other containers if they're on the same network.

docker-compose is additional software that allows you to define and coordinate multi-container applications.


[[images]]
[[containers]]
[[sharing images]]
[[volumes to persist data]]
[[docker networks]]
[[docker-compose]]
[[best practices]]
