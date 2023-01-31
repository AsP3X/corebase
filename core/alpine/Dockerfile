FROM alpine:latest
LABEL org.opencontainers.image.maintainer="AsP3X"

# update and upgrade the system
RUN apk update && apk upgrade

# install dependencies
RUN apk add curl wget htop nano git