# Docker container for SRAToolKit developed by NCBI Genbank/SRA team.
# CONTAINER VERSION 0.1

# Pull base image.
FROM dockerfile/ubuntu

# :)
MAINTAINER Tazro Inutano Ohta, inutano@gmail.com

# clone repo
WORKDIR /src
RUN wget "http://ftp-trace.ncbi.nlm.nih.gov/sra/sdk/2.4.4/sratoolkit.2.4.4-ubuntu64.tar.gz" && \
    tar zxfv sratoolkit.2.4.4-ubuntu64.tar.gz && \
    cp -r sratoolkit.2.4.4-ubuntu64/bin/* /usr/bin

# Default command
WORKDIR /data
CMD ["bash"]
