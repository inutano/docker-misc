# Docker container for cmatrix, mainly for introduction of docker
#
# VERSION 0.1

# Pull base image.
FROM debian:stable

# :)
MAINTAINER Tazro Inutano Ohta, inutano@gmail.com

# Install packages.
RUN apt-get update && \
    apt-get install -y cmatrix && \
    rm -rf /var/lib/apt/lists/*

# Define default command.
CMD ["cmatrix"]
