FROM ubuntu:latest
LABEL org.opencontainers.image.maintainer="AsP3X"

# update and upgrade the system
RUN apt-get update && apt-get upgrade -y

# install dependencies
RUN apt install -y curl
RUN apt install -y wget
RUN apt install -y nano
RUN apt install -y htop
RUN apt install -y git

# clean up the system by removing the apt cache and lists
RUN apt-get clean && rm -rf /var/lib/apt/lists/*