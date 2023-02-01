FROM ubuntu:latest
LABEL org.opencontainers.image.maintainer="AsP3X"

# update and upgrade the system
RUN apt-get update && apt-get upgrade -y

# install dependencies
RUN apt install -y curl wget nano htop git

# clean up the system by removing the apt cache and lists
RUN apt-get clean && rm -rf /var/lib/apt/lists/*