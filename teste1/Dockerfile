# base image
FROM debian:latest


# install basic apps
LABEL maintainer="manueng"

RUN apt-get update && apt-get upgrade -y
RUN apt-get install python3 -y

RUN apt install git -y
RUN apt-get install python3-pip -y
RUN git clone https://github.com/medeiroslucas/andromeda-desktop
RUN apt install pkg-config libboost-python-dev libboost-thread-dev libbluetooth-dev libglib2.0-dev python-dev -y
RUN pip install gattlib
