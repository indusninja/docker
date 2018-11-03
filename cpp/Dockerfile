FROM gcc

MAINTAINER Prakash Prasad "prakash@prakashprasad.com"

RUN \
  sed -i 's/# \(.*multiverse$\)/\1/g' /etc/apt/sources.list && \
  apt-get update && \
  apt-get -y upgrade && \
  apt-get install -y build-essential && \
  apt-get install -y software-properties-common && \
  apt-get install -y git cmake make && \
  rm -rf /var/lib/apt/lists/*