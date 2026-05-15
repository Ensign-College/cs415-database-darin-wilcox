# A Docker file tells Docker HOW to build the image.
FROM ubuntu:latest

RUN apt-get update
RUN useradd -ms /bin/bash psqluser
USER psqluser
WORKDIR /home/psqluser