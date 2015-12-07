This repo is forked from [docker/dockercraft](https://github.com/docker/dockercraft). The origin dockercraft only support mount local sock of docker, this repo allow user to specify docker tcp endpoint by enviroment variable.

Example:
	
	`docker run -t -i -d -p 25565:25565 -e  DOCKER_REMOTE_URL='127.0.0.1:4243' <image name>`
	


