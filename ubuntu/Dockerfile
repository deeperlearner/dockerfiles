FROM ubuntu:18.04
RUN apt-get update && apt-get install -y \
    curl \
    git \
    python3-pip \
    vim \
    ranger \
    tmux

COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
COPY . /tmp/
