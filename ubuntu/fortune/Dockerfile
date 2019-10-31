FROM ubuntu:latest

LABEL maintainer="laurendc@gmail.com"

RUN apt-get update && apt-get upgrade -y

RUN apt-get install fortune cowsay -y

ENV PATH "$PATH:/usr/games"

WORKDIR /fortune