FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y python3

COPY hello.py /home/hello.py

ENV PERSON_NAME="Violetta"

WORKDIR /home

ENTRYPOINT ["/usr/bin/python3"]
