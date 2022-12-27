A Dockerfile is a text file that contains instructions for building a Docker image. Here are the instructions that can be used in a Dockerfile:

FROM: Specifies the base image for the Docker image.
RUN: Executes a command in the Docker image.
CMD: Specifies the default command to run when the Docker container is started.
LABEL: Adds metadata to the Docker image in the form of key-value pairs.
EXPOSE: Exposes a port on the Docker container.
ENV: Sets an environment variable in the Docker image.
ADD: Copies files from the host machine to the Docker image.
COPY: Copies files from the host machine to the Docker image.
ENTRYPOINT: Specifies the command that is always run when the Docker container is started.
VOLUME: Creates a mount point for data storage in the Docker image.
USER: Sets the user for the Docker image.
WORKDIR: Sets the working directory for the Docker image.
ARG: Declares a build-time variable for the Docker image.
ONBUILD: Triggers a build instruction when the image is used as a base image.
Note that some of these instructions can have additional options and syntax, so it is a good idea to consult the official Docker documentation for more information.


https://docs.docker.com/engine/reference/builder/

