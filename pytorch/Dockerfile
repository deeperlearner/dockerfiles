FROM nvcr.io/nvidia/pytorch:21.06-py3
RUN apt-get update && apt-get install -y \
    curl git vim ranger

COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
COPY . /tmp/
