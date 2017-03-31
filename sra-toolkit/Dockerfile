# Docker container for SRAToolKit developed by NCBI Genbank/SRA team.
# Toolkit VERSION 2.8.2-1

# Pull base image.
FROM ubuntu:14.04.4

# :)
MAINTAINER Tazro Inutano Ohta, inutano@gmail.com

# clone repo
WORKDIR /src
ENV VERSION 2.8.2-1
RUN apt-get update -y && apt-get install -y wget
RUN wget "http://ftp-trace.ncbi.nlm.nih.gov/sra/sdk/${VERSION}/sratoolkit.${VERSION}-ubuntu64.tar.gz" && \
    tar zxfv sratoolkit.${VERSION}-ubuntu64.tar.gz && \
    cp -r sratoolkit.${VERSION}-ubuntu64/bin/* /usr/bin

# Default command
WORKDIR /data
CMD ["bash"]
