# Ubuntu 20.04 LTS (Focal Fossa)
FROM ubuntu:focal

RUN groupadd --gid 9999 dev && \
    useradd --system --uid 9999  --create-home --home-dir /home/dev -g dev dev -s /usr/bin/bash

RUN adduser dev sudo && \
    echo '%sudo ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers    
    
USER dev    
