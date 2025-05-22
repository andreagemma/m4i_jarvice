FROM python:3.12
SHELL ["/bin/bash", "-c"]

RUN apt-get update
RUN apt-get install -y curl
RUN curl -fsSL https://deb.nodesource.com/setup_23.x -o nodesource_setup.sh 
RUN bash nodesource_setup.sh
RUN apt-get install -y nodejs
RUN apt-get install -y python3-pip
RUN apt-get install -y wget
RUN apt-get clean
