[``docker run [OPTIONS] IMAGE [COMMAND] [ARG...]``](https://docs.docker.com/engine/reference/commandline/run/) The `docker run` command first `creates` a writeable container layer over the specified image, and then `starts` it using the specified command.
- ``--detach, -d`` run container in background
- ``--env, -e`` set environment variables
- ``--interactive, -i`` interactive mode
- ``--publish, -p`` publish containers ports to host
- ``env-file`` read in a file of environment variables
- ``--rm`` remove the container when it exits
- ``--tty, -t`` allocate a pseudo-TTY
- ``--workdir, -w`` working directory inside container


[``docker ps [OPTIONS]``](https://docs.docker.com/engine/reference/commandline/ps/) lists containers running
- ``-a`` for all, including containers paused
- ``-l`` for latest created

[``docker logs [OPTIONS] CONTAINER``](https://docs.docker.com/engine/reference/commandline/logs/) retrieves logs present at time of execution 
- ``--timestamps, -t`` shows timestamps

[``docker stop [OPTIONS] CONTAINER``](https://docs.docker.com/engine/reference/commandline/stop/) stops a running container
- ``--time, -t`` wait time before killing