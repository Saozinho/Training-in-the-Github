**In Section 5 of the notes, we learn about using the Docker CLI to interact with the Docker daemon. The Docker daemon pulls the "hello-world" image from the Docker Hub and creates a new container from it. This container runs an executable that generates the output we see in the terminal. The output is streamed from the Docker daemon to the Docker client, which sends it to our terminal.** 

- An image is a combination of a file system and parameters, and it does not have any state attached to it. Once built, it remains the same and can be downloaded, built, and run. On the other hand, a container is the act of running an image.

- To run a Linux shell with Docker, we can use the ``"docker run -it ubuntu bash"`` command. We can then navigate the file system using the ``"ls -la"`` and ``"cd"`` commands.

- Docker Hub is a registry that contains Docker repositories, similar to GitHub for images. A tag is used to version control an image. There are two ways to build a Docker image: by running a Docker container, making changes, and then committing those changes to a new image layer; or by using a Dockerfile, which is a blueprint recipe for creating a Docker image.