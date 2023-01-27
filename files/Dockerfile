# Dockerfile

# Script       : weirdnehal
# Author       : Nehal Ahmed
# Github       : https://github.com/weirdnehal
# Messenger    : https://m.me/nehal.ahmed6
# Email        : misterweird10@gmail.com
# Date         : 19-01-2023
# Main Language: Python

# Download and import main images

# Operating system
FROM debian:latest

# Author info
LABEL MAINTAINER="https://github.com/weirdnehal/"

# Working directory
WORKDIR /SMS-BOMBING/
# Add files 
ADD . /SMS-BOMBING

# Installing other packages
RUN apt update
RUN apt upgrade -y
RUN apt install python

# Main command
CMD ["./SMS-BOMBING.py", "--no-update"]

## Wanna run it own? Try following commnads:

## "sudo docker build . -t weirdnehal/SMS-BOMBING:latest", "sudo docker run --rm -it weirdnehal/SMS-BOMBING:latest"

## "sudo docker pull weirdnehal/SMS-BOMBING", "sudo docker run --rm -it weirdnehal/SMS-BOMBING"
