# docker-iis
Running IIS in Docker

## Install
https://docs.docker.com/docker-for-windows/install/

## Switch to run Windows containers
https://docs.docker.com/docker-for-windows/#switch-between-windows-and-linux-containers

## Usage
Run docker-test.bat

That will download the IIS image (See https://hub.docker.com/r/microsoft/iis/ 1.6GB+ so it will take a bit), copy the local artifacts to the image, and run the container on port 8000.

Open a browser to localhost:8000 to test.
