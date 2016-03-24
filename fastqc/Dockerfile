# Docker container for fastqc, mainly for introduction of docker
#
# VERSION 0.1.1

# Pull base image.
FROM ubuntu:14.04.4

# :)
MAINTAINER Tazro Inutano Ohta, inutano@gmail.com

# Install packages.
RUN apt-get update && \
    apt-get install -y fastqc && \
    rm -rf /var/lib/apt/lists/*

# Define default command.
CMD ["bash"]
