FROM maven:3.3.9-jdk-7
MAINTAINER Xavier Calland <xca@atolcd.com>

# Install Deps
RUN apt-get update && \
  apt-get install -y --force-yes rpm

# Cleaning
RUN apt-get clean
