# DockerRepo
docker info								List system-wide information regarding the Docker installation.
docker --version							List the installed docker version.
docker --help								List the help on any docker command.
docker system prune							Remove all unused containers, networks, images, and optionally, volumes.
docker login								Login into your Docker account.
docker login -u <username>						Login into the Docker account using the username.
docker logout -u <username>						Log out from your Docker account.
docker push <username>/<image_name>					Publish your own container image to Docker Hub.
docker search <image_name>						Search on the Docker Hub for an image.
docker pull <image_name>						Pull the image from a Docker Hub.
docker build	Build Docker Images.
docker git <repo-web-url>						Build Docker Images Using Git.
docker image ls	List Docker Images.
docker image rm <image-name>						Remove Docker Image.
docker image prune							Remove Unused Docker Images.
docker container create -t -i - -name <container-name> <image-name>	Create Docker Container
docker container run -ti <image-name>					Run Docker Container
docker container rename <current-container-name> <new-container-name>	Rename Docker Container
