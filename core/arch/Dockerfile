FROM archlinux:latest
LABEL org.opencontainers.image.maintainer="AsP3X"

# update and upgrade the system
RUN pacman -Syu --noconfirm

# install dependencies
RUN pacman -S --noconfirm curl wget htop nano git